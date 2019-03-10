## Share your work: Publishing your data analysis in R

<p>Figuring out how to streamline analysis, publish them and collaborate with colleagues</p>

Slides and data here: https://github.com/underthecurve/NICAR

- Why publish your data in R?
    - Open source data promotes community and helps alleviate anxiety about getting something wrong (double and triple check)
    - Brings readers into the fold
    - Allows you to fact check with academics

#### File organization management

<p>There are lot's of opinions on how you should manage your workflow and organize your project files.</p>

- Best practices
    - Create a separate folder for each project
    - Have raw data in input sub folder
    - Cleaned data as the output
    - Code and analysis in code or documentation folder

PRO-TIP: Bottom left of main window — use that little drop down to cycle through the chunks and see where you are in the code!

#### Random tips

- Rpubs: Make your code public and shareable.

- Knitting: "Knitting together code and words within the Tidyverse!"

- Kable: Will give a nice formatted table when you knit

- Use variant: github_markdown for a raw markdown file. This will render pretty well on Github!

- purl() will convert your .Rmd into a raw R documentation.

- nbviewer: Create a github repo and use nbviewer to render it pretty well. Github can take forever to render long/complicated code.

#### Sharing your work

<p>There are three main ways to share your work.</p>

- Straight up code
    - Pro: Easy — all you need is r
    - Con: Not many people can read or understand it
    - Con: Not a lot of context

- Rmarkdown
    - Pro: Can convert it into a lot of formats for your colleagues.
    - Pro: Works with Rstudio
    - Con: Tough to do it while you're actually coding

- Jupyter notebook
    - Pro: Can intersperse prose with code to elegantly explain what is happening wih your code
    - Con: Must know Git and Github