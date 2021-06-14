# r_analytics_workshop
Introduction to analytical workflow and methods using R

This workshop assumes a no familiarity with programming, but some experience or need of analytical tools. If you have experience with programming in Python, or in base R, this workshop will still be worthwhile.

We'll cover the basics necessary for a reproducible and efficient analytics workflow. By the end of workshop, you'll have been introduced to functional programming, best practices for creatiing reproducible and understandable analytics, and tools and approaches to managing analytics projects. 

## Workshop Outline

### Day 1

- Discussion: Analytics pain points
- Analytics workflow
- Tour of RStudio 
- Cloning lesson (https://github.com/vanderbilt-data-science/r_analytics_workshop)
- Literate computing with Notebooks
- Grammar of Data Manipulation 
- Grammar of Graphics
- Running analytics projects in GitHub
- Mini-analytics project introduction

### Day 2
- Setting up an analytics project (see https://github.com/vanderbilt-data-science/analytics_r_template)
- Using GitHub issues and GitHub project to manage projects (even if you're the only team member)
- Validating data with pipeline tests
- Exploring data
- Reproducible analytics
- Projects showcase
- Pain Checklist
- Next steps

## Pre-Workshop Preparation

Before the workshop complete the following to make sure you have all the software you'll need installed and ready to go. If you need assistance, there will be a last-minute clinic 1/2 hour before the start of the workshop. See below for full instructions on each step.

**Prep Steps**

- [ ] Install R
- [ ] Install RStudio
- [ ] Install and test packages 
- [ ] Sign up for GitHub
- [ ] Install git
- [ ] Connect to GitHub
- [ ] Test out git/GitHub/RStudio integration

### Installing R

Visit https://cran.rstudio.com/ and select "Download and R for [your OS]". Select the "Base" option on the download page.  Once the file is downloaded, install the software.   

Also download and install Rtools if you are on Windows--you will find the link below Base on the list.


### Installing RStudion

Visit https://rstudio.com/products/rstudio/download/ and download the free version of RStudio for your operating system. 

### Installing and Testing Packages

Once R and RStudio are download, load RStudio, and copy-paste the following code in the console:

```r
install.packages("tidyverse")
install.packages("janitor")
install.packages("devtools")
install.packages("assertr")
install.packages("readxl")
install.packages("glue")
install.packages("knitr")
```

## GitHub Signup

If you do not already have a GitHub account, please visit https://github.com/ and make one. See https://happygitwithr.com/github-acct.html for advice. 


##  Git Install

Visit https://git-scm.com/downloads and select the download for your operating system. Once the software has downloaded, execute it. 

See https://happygitwithr.com/install-git.html for step-by-step guidance. 

Set up your profile for your local git by following the directions at https://happygitwithr.com/hello-git.html. 

## Connecting to GitHub

New installations of git on MacOS and Windows SHOULD make use of built-in authentication so that you will not need to log into GitHub each time you perform an operation on a remote repo. It you find yourself having to sign in to GitHub when pushing or pulling, follow the guidelines at https://happygitwithr.com/connect-intro.html to set up caching or SSH keys. 

If you are on a Mac, and are not able to access git from RStudio, execute the following commands from with a terminal window:

```
xcode-select --install  
sudo xcode-select -switch /Library/Developer/CommandLineTools
```

## Testing Out Git/GitHub/RStudio

To test out whether RStudio is integrated with git on your computer, we will clone the repository locally to your computer. 

Click on the green "Clone or download" button on this page, and copy the web URL listed there. Start up RStudio, click on 'File' on the menu, select 'New Project', the click on 'Version Control', 'Git', and paste the URL into the Repository URL field. If this repo is downloaded as an R project, your integration has worked. If not, put up your Problem Sticky for assistance. 

