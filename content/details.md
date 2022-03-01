---
title: Workshop Details
---

## Pre-work

You need to have [R](https://cloud.r-project.org/) and [RStudio](https://www.rstudio.com/products/rstudio/download/) installed on the computer you will use for this workshop. Installing the packages **here**, **renv**, **reprex**, **devtools** in advance is recommended. If you will be using a Windows machine for the workshop, please install [Rtools](https://cran.r-project.org/bin/windows/Rtools/rtools40.html) (note that this is a *program* not a package). 

```
packages <- c("here", "renv", "reprex", "devtools")
install.packages(packages)
lapply(packages, library, character.only = TRUE)
```

Once you have **devtools** installed, install the package **lookup** from GitHub:  

```
devtools::install_github("jimhester/lookup")
```
<b style='color:red;'>Note: please do NOT install the package 'lookup' found on CRAN. This is a different package entirely than what we will use in this workshop.</b>

We will be using [gitter](https://gitter.im/Idaho-ag-stats/2022-what-they-forgot-workshop#) for the class chat, which requires a account with either GitHub, GitLab or Twitter. If you do not have one of those, please get an account ([GitHub](https://github.com/signup). 

A Zoom connection is also required since this workshop will be held online

---------------------

We will hold a **Session Zero** February 28 at 3-4 pm to help orient everyone to course expectations, check your set-up, assess needs and vote on some optional topics to address. Please attend if you can. 

## Schedule

### Monday, February 28

3:00 - 4:00 Session Zero 

### Tuesday, March 1

2:00 - 3:30  Settings & Practices for Reproducible Research  
3:30 - 3:45  Break  
3:45 - 5:00  Workflow for Reproducible Research  

### Thursday, March 3

2:00 - 3:30  R set-up & maintenance  
3:30 - 3:45  Break  
3:45 - 5:00  debugging   

### Tuesday, March 8

2:00 - 3:30  Building reproducible examples  
3:30 - 3:45  Break  
3:45 - 5:00  Finding help in R   

### Thursday, March 10

2:00 - 3:30  Extra topics   
3:30 - 3:45  Break  
3:45 - 5:00  Extra topics  
