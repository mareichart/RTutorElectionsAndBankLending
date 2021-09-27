This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

This interactive RTutor problem set is based on the paper “Electoral Cycles in Savings Bank Lending”, published in 2017 by Florian Englmaier and Till Stowasser.

Link to the paper: https://academic.oup.com/jeea/article/15/2/296/2691493?login=true

The goal is to determine the causal effect of county elections on savings bank lending, showing that savings banks systematically adjust their lending to the local election cycle.

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
install.packages("RTutor",repos = c("https://skranz-repo.github.io/drat/",getOption("repos")))

if (!require(devtools))
  install.packages("devtools")

devtools::install_github("mareichart/RTutorElectionsAndBankLending")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorElectionsAndBankLending)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorElectionsAndBankLending")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorElectionsAndBankLending",
       auto.save.code=TRUE, clear.user=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
