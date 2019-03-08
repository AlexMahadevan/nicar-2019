### Building Your Own database

Why?
- Competitive edge, dataset nobody has
- End up being a public service, informing the public on something they don’t know, hard to fix a problem if you don’t know the extent of the problem
- Nothing as satisfying as building your own aritisnal database

Why not???
- It already exists a database format, on’t rebuild a thing that exists and is good
- Someone else has already done it (but maybe another iteration?)
- The work involved is insane and will kill you

- No one size fits all
- Work is tedious and exacting
- Need a full game place before you even start
    - Going to make mistakes along the way
    - And might think of something you want along the way, don’t let that happen

We’re doing the government’s job for it.

Examples: 

Fatal Force
- Built using news clips, social media and some records requests

What are the stories you want to get out of this: if you don’t put the columns in your need then your database is worthless (example, mental health column, weapons, column, what they were doing(armed vs. unarmed))

Gun Violence in schools 
- Common core of data at the department of education
- Private school survey, get those going backwards in time,

Unsolved homicides
- Indianapolis keeps data in written log, for example
- Early on, have deep conversations with the departments
- Besttool is a phone

Will craft

- Datase on jury selection about Curtis flowers, database from every time he excluded a black juror
- Spent two years: went through literal logs
- Can also surface new stories about the neglect of important issues

How do build a database form scratch
- Web scraping
- Public records
- News reports
- By hand

Utility versus feasibility (this is about how to choose columns)

- For police shootings, find out how many people had run-ins with same officer, but the amount of work was too big of a barrier
- If the only time you cn get something is 25% of the time, skip it because it might be 
- Even if you fail, you still are proving some public service, or test out on a small region then expand it out

Early vs. late grouping
- Think about what things ou might want to be very specific but may whittle down later
- Talk to experts to figure out how specific to get
- Example, machete versus sharp object

Standardization
- Vehicular homicide example
- Race and ethnicity, separate or together

Scope versus time

- This is how you get buy in
- Always overestimate the timeframe
- Do one city first, then extrapolate it

Thinking about the story
- No utility in keeping a field on right versus left handed, so you need to think about what the end product is

Tools
- Excel
- Google Sheets (for multiple people entering data)
    - Google forms is the solution
- SQL databases
- Django

How do we build it

A team approach
- Create fail safes
    - 20 people entering data? Prevent one bad egg from ruining the batch, one person who puts in bad data. One fields is literally your name, so you can see if someone has been putting in bad data, then remove their subset
    - Look up ProPublica crowdsource 
- Clear standards for data entry
    - Police shootings: what does attacking mean?
- Spot checking
    - No matter how good you are, you’re going to mess up
    - Check one or two entries a day just to be sure
- Programatic approach
    - Do all of the above in a program!
    - Ideal if possible, because it takes less time
    - But, know he to use technology and when not to
- Need to be able to OCR (except handwritten docs)
    - Can train OCR for specific handwriting (Farenholdt example)
    - Hand check the data after you OCR to make sure your program is running correctly

Pitfalls
- Huge moneyed time investment
    - Need to make sure its worth the time
- Could be competitive
    - Guardian versus the Washington Post
    - Scope it out ahead of time and make sure someone isn’t months ahead of you
- It’s a gamble
    - We don’t know what the results will be
    - Don’t let reporters go down the rabbit hole
- It’s fragile
    - It’s technically possible to delete the entire project
    - Always back everything up
    - Google Sheets has version control!
- Do you keep up with it?
    - Police shootings versus school shootings? Latter is way easier to keep up with
- 
- 
- SURVEYS FOR COLLECTING DATA
    - They have polling people
    - Story on how DC’s tax affix had bad addresses, sent out postcards to the addresses and the bounce back rate was they survey
    - Surveys are useful but be wary of statistical significance
    - Crowdsourcing?

- Picking fields?
    - Do a test run, you can quickly go back and add a field 
    - Always write out a methodology for a database
        - Academics will give you feedback on this
        - “What would you want to know if I build this?”

- How do you get news clips?
    - Lexis Nexis, Google News
    - Came up with specific search terms
    - Spelled out on paper so you know how it will work
