
# Workshop: Twitter Text Analytics for R

## Sponsored by 
* [Project Mosaic](https://projectmosaic.uncc.edu/)

## Date, Time and Location

* Sept 27-29 2016 

* 10am - 12pm

* CHHS 386
 
## Instructor

* [Ryan Wesslen](http://wesslen.github.io)

This workshop will explore text analysis techniques for Twitter data. 

These materials were made referencing original materials by [Pablo Barber&aacute;](http://pablobarbera.com/), who created similar workshop materials for a workshop sponsored by [Quantitative Methods Working Group, European University Institute](https://sites.google.com/site/qmwgroup/). Much of the introduction text below was used from Pablo's workshop. Please see his [original workshop materials](https://github.com/pablobarbera/eui-text-workshop).

Additional content (via Pablo Barber&aacute;) were based on materials prepared by [Dan Cervone](http://dcervone.com/), [Alex Hanna](http://alex-hanna.com), [Ken Benoit](http://www.kenbenoit.net/), [Paul Nulty](https://github.com/pnulty), [Kevin Munger](https://github.com/kmunger), and [Justin Grimmer](http://www.justingrimmer.org/).

If you're serious about learning social media and text analysis, I highly suggest the tutorials, R packages and cutting-edge research by all of the great researchers above.

## Description

The popularity of text as data is increasing rapidly within the social sciences. “Scholars have long recognized this, but the massive costs of analyzing even moderately sized collections of texts have hindered their use in political science research” (Grimmer and Stewart 2013) and elsewhere in the social sciences. This situation has changed with increasing computing power and more capable computing tools. In the coming years, the relevance of text data will further increase as more and more human communication is recorded online. 

This workshop provides an introduction to text analysis using R, focusing on Twitter datasets. The workshop is over three days.

## Schedule for Project Mosaic Workshop

| Day 1: Tues Sept 27 | Topics                                                  |
| ------------------- | ------------------------------------------------------- |
| Lecture             | Why study Twitter?                                      |
| Case Study          | [Finding Carolina Panther Tweets](Day1/exercise1.Rmd)   |

| Day 2: Wed Sept 28  | Topics                                                  |
| ------------------- | ------------------------------------------------------- |
| Lecture             | Introduction to text analysis with `quanteda`           |
| Case Study 1        | [Analyzing Pres Candidate Tweets: Data Prep](Day2/exercise2-dataprep.Rmd) |
| Case Study 2        | [Text Visualizations](Day2/exercise2-textvisual.Rmd) |
| Case Study 3        | [Sentiment Analysis](Day2/exercise2-sentiment.Rmd) |
| Case Study 4        | [Supervised Machine Learning](Day2/exercise2-supervised.Rmd) |

| Day 3: Thur Sept 29 | Topics                                                  |
| ------------------- | ------------------------------------------------------- |
| Lecture             | Topic modeling with `topicmodels`                       |
| Case Study          | [Analyzing Charlotte Twitter Topics](Day3/exercise3.Rmd)|


## Setup and Preparation

You will need [R](https://cran.r-project.org/) and [RStudio](https://www.rstudio.com/) installed. [Follow the instructions here to install both](https://github.com/pablobarbera/eui-text-workshop/blob/master/installing_RStudio.pdf).

Also, we will be using several R packages including:

* `ggplot2`
* `dplyr`
* `ggmap`
* `stringi`
* `tm`
* `quanteda`
* `topicmodels`
* `LDAvis`

Please install these packages before hand to avoid any delays.

### Instructions for using course materials on GitHub ###

You have two options for downloading the course material found on this page:  

1.  Most simply, you can choose the button on the right marked "Download zip" which will download the entire repository as a zip file.

2.  You can "clone" repository, using the buttons found to the right side of your browser window as you view this repository.  This is the button labelled "Clone in Desktop".  If you do not have a git client installed on your system, you will need to [get one here](https://git-scm.com/download/gui) and also to make sure that [git is installed](https://git-scm.com/downloads).  This is preferred, since you can refresh your clone as new content gets pushed to the course repository.  (And new material will get actively pushed to the course repository while this course takes place.)

You can also subscribe to the repository if you have [a GitHub account](https://github.com), which will send you updates each time new changes are pushed to the repository.
