Plan for this workshop series
=============================

This workshop series is geared toward learning basic data management in `R`. This includes tasks like manipulating variables, creating new variables, subsetting data, reshaping data, and merging. We will also cover some introductory regular expression applications. In this workshop series we will cover only basic visualization methods in `R`. For a more thorough introduction to to `ggplot2`, see my workshops on [data visualization](https://github.com/thereseanders/Workshop-Intro-to-ggplot2)and creating [maps in `R`](https://github.com/thereseanders/Workshop-Maps-in-R).

Sessions:

1.  [**Intro R 1**](https://github.com/thereseanders/Workshop-DataManagement-R/tree/master/Session1) (working directories, arithmetic, logical operators, basic indexing, data types, basic functions such as `sum()`, `mean()`, `names()`, `seq()`, `rep()`, etc.).
2.  [**Intro R 2**](https://github.com/thereseanders/Workshop-DataManagement-R/tree/master/Session2) (reading and writing data, dealing with missing data, data frames, indexing on data frames, getting an overview of the data with multivariate numerical and graphical summaries).
3.  [**Basic data management**](https://github.com/thereseanders/Workshop-DataManagement-R/tree/master/Session3): Introduction to `dplyr`.
4.  [**Data shaping and reshaping**](https://github.com/thereseanders/Workshop-DataManagement-R/tree/master/Session4): `tidyr` in connection with `dplyr`.
5.  [**Introduction to string operations**](https://github.com/thereseanders/Workshop-DataManagement-R/tree/master/Session5) with `stringr`. Primer on web-scraping.
6.  **Bringing it all together**: Advanced problems with `tidyr`, `dplyr`, and `stringr`.

Getting started in `R`
======================

`R` is a programming language for statistical computing and data visualization, that is a open source alternative to commercial statistical packages such as Stata or SPSS. `R` is maintained and developed by a vibrant community of programmers and statisticians and offers many user-written packages to extend basic functionality.

In this workshop, we will be using `R` together with the integrated development environment (IDE) **RStudio**. In addition to offering a 'cleaner' programming development than the basic `R` editor, RStudio offers a large number of added functionalities for integrating code into documents, built-in tools and web-development. To get started, please download the latest version of RStudio and `R` from this website:

<https://www.rstudio.com/products/rstudio/download/>

Getting Help
============

The key to learning `R` is: **Google**! This workshop will give you an overview over basic `R` functions, but to really learn `R` you will have to actively use it yourself, trouble shoot, ask questions, and google! The `R` mailing list and other help pages such as <http://stackoverflow.com> offer a rich archive of questions and answers by the `R` community. For example, if you google "recode data in r" you will find a variety of useful websites explaining how to do this on the first page of the search results. Also, don't be surprised if you find a variety of different ways to execute the same task.

RStudio also has a useful help menu. In addition, you can get information on any function or integrated data set in `R` through the console, for example:

``` r
?plot
```

In addition, there are a lot of free `R` comprehensive guides, such as Quick-R at <http://www.statmethods.net> or the `R` cookbook at <http://www.cookbook-r.com>.

Acknowledgements
================

This workshop series was first taught in September 2016 as part of the data science training for the [Security and Political Economy Lab](https://dornsife.usc.edu/spec) at the University of Southern California.

The first two intro sessions to basic `R` programming are heavily inspired by the first chapter of Kosuke Imai's (2017) book "Quantitative Social Science. An Introduction" (http://assets.press.princeton.edu/chapters/s11025.pdf).
