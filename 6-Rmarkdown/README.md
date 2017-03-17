**Dynamic Documents with R Markdown**

by Garret Christensen & Julia Clark

Berkeley Initiative for Transparency in the Social Sciences/Berkeley Institute for Data Science

----------
# Intro to R and RMarkdown

Before we begin, make sure you have R and RStudio installed:

1. Download and install [R](https://cran.rstudio.com/)
2. Download and install [RStudio](https://www.rstudio.com/products/rstudio/download/)

## Basic R
First, we're going to work through a very basic introduction in R, for which you will need the script file "r_intro.R". 

## RMarkdown
Next, we'll take a look at RMarkdown, using the following files which you should download (or fork and clone):

1. **RMarkdown_demo.Rmd**---R Markdown file that introduces you to basic concepts, then runs some of the R code from the "r_inro.R" file, creating the output file "RMarkdown_demo.pdf". It also includes some formatting tips if you want a nice-looking, Latex-formatted academic paper, complete with citations, footnotes, etc.
1. **RMarkdown_slides.Rmd**---Another R Markdown example that makes HTML slides.
1. **WASHBpublic_mock.dta**---Data for analysis.
1. **my_bib.bib**---Bibliography in BibTeX format to use in RMarkdown_demo.Rmd
1. **de-identification_indirect.png**---Example image we'll embed in RMarkdown_demo.Rmd

There are other example files in here from previous workshops that you can also play around with in your spare time, including: 

1. **RMarkdownHTMLExample.Rmd**---R Markdown file for use in R. When successfully run, it will load data (the WASHpublic_mock.dta file) and run three basic regressions. It uses the stargazer package to create nicely formatted HTML regression tables in outputR.html. That table is included in the final combined output: RMarkdownHTMLExample.html.
1. **RMarkdownPDFExample.Rmd**---RMarkdownPDFExample.Rmd is similar to the above but makes PDF output. When successfully run, it will load data (the WASHpublic_mock.dta file) and run three basic regressions. This uses the stargazer package to create nicely formatted LaTeX regression tables (outputR.tex). The combined output file is RMarkdownPDFExample.pdf.
1. **RMarkdownWordExample.Rmd**---Tons of people use Word. So there's an option for that, too.

(Don't worry about the Rproj or Rhistory files you may see. That's just R Studio being friendly and keeping track of everything in the background for you if you organize the directory as an R Project.)

# Step One

That's it. There's one step. Open a .Rmd file and click Knit. It's beautiful. You don't even have to worry about filepaths, and version control is built right in.

# Activity
Next, we'll have some time for another choose-your-own-adventure activity. Options include:

- Go through some of the basic R tutorials using 'swirl'. Do to this, follow the instructions at the end of the  'r_intro.R' file.

- If you're a little more comfortable in R, try writing your own RMarkdown document. There are lots of tips on the [RStudio website](http://rmarkdown.rstudio.com/lesson-1.html) and a good [reference guide here](https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf). If you want to tinker with the RMarkdown formatting to write a really nice looking academic paper, check out [this link](http://svmiller.com/blog/2016/02/svm-r-markdown-manuscript/)

- Continue with the replication exercises from yesterday, and write up your results using Stata +  Markdoc
