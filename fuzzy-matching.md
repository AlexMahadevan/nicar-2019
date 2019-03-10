## Finding needles in haystacks with fuzzy matching

<p>Here we learn how to use the command line to clean up dirty data.</p>

What is it?
- Matching two things that aren't quite the same but refer to the same thing
    - Usually names of people or places
    - Theresa May, Theresa Mary May, The Right Honorable Theresa May

- Examples
    - Guardian story on offshore tax accounts
    - jade: Myanmar's Big State Secret
    - U.N. paying blacklisted diamond company

open . will open the folder you're looking at in the console on your Desktop.

Who's on both Bloomberg and Forbes Billionaire's list
Backslash (\) breaks up your bash into multiple lines
-- is a flag, extra bits of information we give to a tool on the command line to tell it how to work


--fields1 can be shirtened to -1

Don't forget the carrot

Naive approaches to fuzzy matching
- ignore things: Mr. Mrs., case, non-latin, non-alphanumercs(dashes)

Viktor Orban example:

which cia leaders went to Davos?

Levenshtein
Looks at the % they are similar based off the number of changes that would need to happen for it to be a match, good for catching typos


which world leaders are also on the forbes list?

false positives and false negatives

false positives: when the computer thinks two things are a match, but they actually aren't

metaphone algorithm

looks at how words are pronounced, good when people use the wrong spelling, for example, Scott's lobbying story, assistants were spelling names totally wrong but still phonetic

which names on the leders list are facing UN sanctions

Bilenko algorithm, machine learning based approach, datamade

Caveats

Same name doesn't mean same person
medium sized data only
every row neds to be matched with another row
multipy the number of rows in the two giles, if in the millions, might be too big

bit.ly/2H4xv23

