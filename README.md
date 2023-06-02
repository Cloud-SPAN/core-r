# Introduction to R for complete beginners

Cloud-SPAN develops training in **Sp**ecialised **an**alyses for environmental 'omics with Cloud-based High Performance Computing and is funded by the [UKRI innovation scholars award](https://www.ukri.org/news/initiatives-boost-health-and-bioscience-skills-and-industry/) ([MR/V038680/1](https://gtr.ukri.org/projects?ref=MR%2FV038680%2F1)) the Natural Environment Research Council ([NE/X006999/1](https://gtr.ukri.org/projects?ref=NE%2FX006999%2F1#/tabOverview)).

## Overview

This online two-hour workshop is an introduction to R for complete beginners.  It teaches you how to find your way round RStudio, use the basic data types and structures in R and how to organise your work with scripts and projects. It also teaches you how to import data, summarise it and create and format a graph. The workshop assumes no prior experience of coding.

R is a free and open source language especially well-suited to data analysis and visualisation and has a relatively inclusive and newbie-friendly community. R caters to users who do not see themselves as programmers, but then allows them to slide gradually into programming.

## Learning outcomes

After this workshop the successful learner will be able to:

-   find your way around RStudio

-   use the basic data types and structures in R

-   organise your work with scripts and projects

-   import data, summarise it and create and format a graph

# Pre-course instructions for participants

You should install the following **before** the workshop

- R version 4.0 or higher
- RStudio (2023)
- these packages: `tidyverse`


## Installing R

Download the pre-compiled binary for your OS from https://cloud.r-project.org/ and install. More specifically:

**For Windows**

Click "Download R for Windows", then "base", then "Download R 4.x.x for Windows". This will download an `.exe` file; once downloaded, open to start the installation. You can accept all the defaults.

**For Mac**

Click "Download R for (Mac) OS X", then "R-4.x.x.pkg" to download the installer.
Run the installer to complete installation. You can accept all the defaults.

**For Linux**

Click "Download R for Linux". Instructions on installing are given for Debian, Redhat, Suse and Ubuntu distributions. Where there is a choice, install both `r-base` and `r-base-dev`.

## Installing R Studio

Download and install the version for your OS from: https://posit.co/download/rstudio-desktop/
You can accept all the defaults.

**For Windows with no admin rights**

Download the `.zip` source archive under "Zip/Tarballs". Extract the files to a folder where you have write access. Open the `bin` folder and find the RStudio program: it is named `rstudio-xxxxxxx.exe` (where xxxxxx is a version number), but the file extension will typically be hidden, so look for `rstudio-xxxxxxx`. Double-click the executable or use the shortcut to open.

## Installing packages

### From CRAN
Once you have installed R and RStudio, start RStudio up and go to the Packages tab in the bottom right pane; click Install and type the name of the package you want to install in the box that appears. Then wait until you get the cursor (>) back in the console window.

## Having problems?
If installing R and RStudio is tricky or impossible with your set up (e.g., if you only have a chrome book) then you can use https://posit.cloud/. This is a version of RStudio that runs in your browser. It is free for 15 hours but you will need to make an account. You will still need to install packages.
