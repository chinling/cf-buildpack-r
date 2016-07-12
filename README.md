# CloudFoundry buildpack: R

This is a CloudFoundry buildpack for applications which use
[R](http://www.r-project.org/) for statistical computing and [CRAN](http://cran.r-project.org/) for R packages.

It's a fork from https://github.com/alexkago/cf-buildpack-r which in turn forked from the R buildpack for Heroku.
The version built by Alex contains reference to R binary that is old, and one of the purpose of 
this is to upgrade the version and perform some minor script cleanup. It is still work in progress, many
work in the scripts remains dirty

R is ‘GNU S’, a freely available language and environment for statistical computing and graphics which provides
a wide variety of statistical and graphical techniques: linear and nonlinear modelling, statistical tests, time
series analysis, classification, clustering, etc. Please consult
the [R project homepage](http://www.r-project.org/) for further information.

[CRAN](http://cran.r-project.org/) is a network of ftp and web servers around the world that
store identical, up-to-date, versions of code and documentation for R.

