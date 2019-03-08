## Share your work: Publishing your data analysis in R

<p>Figuring out how to streamline analysis, publish them and collaborate with colleagues</p>

Slides and data here: https://github.com/underthecurve/NICAR

* Open source data promotes community and helps alleviate anxiety about getting something wrong (double and triple check)

* Brings readers into the fold

#### File orgaization management

Example:

Let's look at Census data from Newport Beach.

File organization: Lot's of opinions:

Create a separate folder for each project. Exampe: the NICAR folder. Have raw data in input sub folder. Cleaned data as the output. Processing and analysis in code or documentation folder.

Bottom left of main window: Use that little drop down to cycle through the chunks and see where you are in the code.

Rpubs: make your code public and shareable.

Knitting: "knitting together code and words within the Tidyverse"

Kable: will give a nice formatted table when you knit

Use variant: github_markdown for a raw markdown file. This will render pretty well on Github!

purl() will concert your .Rmd into a raw R documentation.

nbviewer: Create a github repo and use nbviewer to render it pretty well. Github can take forever to render long/complicated code.

Three ways of sharing your work.

Straight up code

pros: easy all you need is r

con: not many people can read or understand it
Not a lot of context.

Rmarkdown

Pros: Can convert it into a lot of formats for your colleagues. 

Cons: Tought to do it while you're actually coding

