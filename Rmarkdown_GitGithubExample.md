Git\_GitHub Ex
================
Courtney Chan
September 13, 2018

Lecture Why use Git Provides version control Difficult to use sometimes - because it will be tedious to keep up with the updates But keeps things very organized - don't have to have multiple version files locally

Git will keep track of each version you commit to - you can also comment on the versions to explain why you did it

Git will remind you, keep you acccountable, record what changes you made

Git watches everything inside of the directory you assigned it to - data file, markdown file, plots exporting etc.

Will show you what changed when it changed Will keep track of what other people do as well Makes you resolve conflicts in real time

Git is the local program - while GitHub is like drop box but GitHub won't update automatically need to push

Rstudio helps you to use Git - can use Git seperately for example source tree

Commit will keep track what has changed from previous file - need to write your own message to yourself as to what changed and why

Can review on Github what someone else is doing on different/same documents - read the summary rather than running through the whole document

Need to save the document in Rstudio first This creates a file to be saved then on Git and Github

Don't put patient data on dropbox - cannot protect confidentiality

Branch, merge, fork and clone etc. other stuff

Creating repository - can be public or private amongst collaborators or just yourself

Create a local repository on your own computer for your R project

So instead of making a normal R project not linked to Git - make a project that is linked to Git

Git tab is where you write in the comments, interact with Git

ReadMe - can ignore this but it is a list of document types that Git does not keep track of - .Rproj.user etc.

In commit window - will show list of things that have changed in the file

Git tab will now be empty because nothing new

Create new R markdown, knit as normal, save it in the Git project folder locally

Need to commit then also push can see the comment "your branch is ahead by 2 comments or whatever"

Need to remember to push - main source for conflicts People will work independently - and all of that work all of the commits can possibly clash

Read me can act as navigation table of contents, detail on project,

Github treats Md files differently from other files

R Markdown
----------

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00

Including Plots
---------------

You can also embed plots, for example:

![](Rmarkdown_GitGithubExample_files/figure-markdown_github/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.

I'm an R Markdown document!

Section 1
=========

Here's a **code chunk** that samples from a *normal distribution*:

``` r
samp = rnorm(100)
length(samp)
```

    ## [1] 100

Section 2
=========

I can take the mean of the sample, too! The mean is -0.0411023.
