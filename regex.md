## Regular Expressions for the Rest of Us

<b>Christian McDonald — University of Texas</b>

<p>Learning to use regex to quickly clean extremely dirty data</p>

### Overview

* A concept as much as a language.
    * All languages have the ability to use regex

### Key concepts

Let's say we have a column of data with a bunch of phone numbers, but want them to have parenthesis

Search and replace? Sure. But if all the numbers are different, then that doesn't work. Enter regex.

Search for a pattern instead!

Tokens: Signify what we are looking for. They're commands.
    * ^ = the beginning of a line
    * * = will find zero or more of whatever preceds it.

\ turns letters into tokens
    * \d will find any number or character

Once collected you can spit it back out.

You can calso collect multiple things in a group.

Example workflow: Pull column out of excel into a text editor. Run regex, then put it back.

NOTE: Checkout Socrata.

Tip: Keep Regex 101 in PHP so the colors remain useful.

Keep an eye on matches as you build a regex. If you lose some matches there is a problem with the data you need to look at.
i.e. Bee Cave screwed up our firss regex attempt because there is a space. So we add square brackets and a space so we can capture all words AND spaces.

Asterisk: If you find it keep going, if youdon't fint it keep goig
Plus sign, you have to find this

Remember, brackets let us grab more than one thing.

What now?

Now go into subsitution. Here, we'll write another regex! 
$ = Grabs each group you're looking for. 

Now copy from regex101 and paste it back into Excel! 

"It's so beautiful!"

You can also do all of this in a text editor, like VisualStudioCode. Just put the regex expression into find, and the replace regex expression into the replace 

What if you want to replace a period with a comma.

"You have to account for it, somehow."



