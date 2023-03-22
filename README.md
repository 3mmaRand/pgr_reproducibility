
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3859818.svg)](https://doi.org/10.5281/zenodo.3859818)

# Introduction to Reproducibility in R

Training programme for first year PhD students on the White Rose Universities (York, Sheffield, Leeds) DTP. It is designed and delivered by [Emma Rand](https://www.york.ac.uk/biology/our-staff/emma-rand/) of The University of York.

## Overview

An increase in the complexity and scale of biological data means biologists are increasingly required to develop the data skills needed to design reproducible workflows for the simulation, collection, organisation, processing, analysis and presentation of data. Developing such data skills requires at least some coding, also known as scripting. This makes your work (everything you do with your raw data) explicitly described, totally transparent and completely reproducible. However, learning to code can be a daunting prospect for many biologists! That’s where an [Introduction to reproducible analyses in R](https://github.com/3mmaRand/pgr_reproducibility) comes in!

R is a free and open source language especially well-suited to data analysis and visualisation and has a relatively inclusive and newbie-friendly community. R caters to users who do not see themselves as programmers, but then allows them to slide gradually into programming.


## Prerequisites

I recognise that people will enter this training with a diverse range of previous experience in R. This is a challenge to manage but the aim is for everyone to get something out of the training no matter where they start. 
There will be sessions for those with and without previous experience. I recommend you:

-   sit close to the front of the class if you are completely new to R and towards the back if you have some experience 
-   bring headphones to allow you to ignore tutor-led material when needed

Pre-course instructions for participants are given below.

## Philosophy and approach

It is impossible to cover everything to you might ever need! Different people will use different methods and tools. Topics have been chosen because they are: foundational, widely applicable and transferable conceptually.


## Learning outcomes

After this workshop the successful learner will be able to:

-   Find their way around the RStudio windows
-   Create and plot data using the base package and ggplot
-   Explain the rationale for scripting analysis
-   Use the help pages
-   Know how to make additional packages available in an R session
-   Understand what is meant by the working directory, absolute and relative paths and be able to apply these concepts to data import
-   Summarise data in a single group or in multiple groups
-   Recognise tidy data format and carry out some typical data tidying tasks
-   Develop highly organised analyses including well-commented scripts that can be understood by future you and others
-   Use R Markdown to produce reproducible analyses, figures and reports

# Pre-course instructions for participants

## Precourse survey

To help me direct you to useful training and manage diversity in previous experience during the sessions, please complete this form to indicate your current level: https://forms.gle/cpSjdcjVa7niz6iq5

## Facilities

There are Windows PCs at the venue and you are not required to bring your own machine. Participants from outside of York will be provided with a temporary IT account. However, if you prefer to work on your own machine please follow the instructions in [Computing requirements](#computing-requirements)

# Schedule for workshop


1015 - 1030
Tutor-led for Everyone: [Introduction and Principles of reproducibility](https://3mmarand.github.io/pgr_reproducibility/slides/01_intro_and_principles_of_repro.html)

1030 - 1200
Tutor-led for Beginners:  [Introduction to R and working with data](https://3mmarand.github.io/pgr_reproducibility/slides/02_intro_to_r_and_working_with_data.html)
or
Supported learning for those with some R experience [Tidying data and the tidyverse including the pipe](https://3mmarand.github.io/pgr_reproducibility/slides/04_tidying_data_and_the_tidyverse.html)

1200 - 1245 Lunch 

1245 - 1330
Tutor-led for Everyone: [Project-oriented workflow](https://3mmarand.github.io/pgr_reproducibility/slides/03_rstudio_projects.html)

1330 - 1430
Tutor-led for Everyone:[ R Markdown for Reproducible Reports](https://3mmarand.github.io/pgr_reproducibility/slides/06_r_markdown_for_reproducible_reports.html)

1430 - 1515 Tea and coffee break with Special Interests Group launch

1515 - 1645
Continuation of Tutor-led for Everyone:[ R Markdown for Reproducible Reports](https://3mmarand.github.io/pgr_reproducibility/slides/06_r_markdown_for_reproducible_reports.html)






# Computing requirements

Laptops should have the following installed **prior** to attending attempting the materials.

- R version 4.0 or higher
- RStudio (1.4)
- OS-specific development tools as detailed below
- these packages from CRAN: `devtools`, `usethis`, `tidyverse`, `janitor`, `rticles`, `bookdown`, `tinytex`
- Once `tinytex` is installed, run: `tinytex::install_tinytex()`

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

Download and install the version for your OS from: https://rstudio.com/products/rstudio/download/#download.
You can accept all the defaults.

**For Windows with no admin rights**

Download the `.zip` source archive under "Zip/Tarballs". Extract the files to a folder where you have write access, e.g. `C:\Users\username\RStudio`. In this folder, open the `bin` directory and find the RStudio program: it is named `rstudio.exe`, but the file extension will typically be hidden, so look for `rstudio`. Right-click this executable to create a desktop shortcut. Double-click the executable or use the shortcut to open.

## Development Tools
Some additional tools may be required to compile R packages from source.

**For Windows with no admin rights**

Download the latest (recommended) Rtools40 installer, Rtools.exe, from https://cran.r-project.org/bin/windows/Rtools/. Run the installer keeping the default settings.

**For Windows with admin rights**

Download the latest Rtools installer from https://cran.r-project.org/bin/windows/Rtools/. Run the installer making the following selections: keep the default settings for the installation location and components to install; check the box to add rtools to the system PATH.

**For Mac**

Install XCode. Either:

Download and install XCode from the Mac AppStore: http://itunes.apple.com/us/app/xcode/id497799835?mt=12
Within XCode go to Preferences : Downloads and install the Command Line Tools
Or for a smaller download size:

Register as an Apple Developer (free) here: https://developer.apple.com/programs/register/
Download the Command Line Tools for XCode appropriate for the version of OS X you are running from here: https://developer.apple.com/downloads/

**For Linux**

If you installed r-base-dev, when installing R, you should have all you need to build packages from source. Otherwise return to the instructions for installing R for your distribution and follow the instructions there to install the additional tools.

## Installing packages

### From CRAN
Once you have installed R and RStudio, start RStudio up and go to the Packages tab in the bottom right pane; click Install and type the name of the package you want to install in the box that appears. Then wait until you get the cursor (>) back in the console window.

## RStudio Cloud
If installing R and RStudio is tricky or impossible with your set up (e.g., if you only have a chrome book) then you can use https://rstudio.cloud/. This is a version of RStudio that runs in your browser. It is free for 15 hours but you will need to make an account. You will still need to install packages.

# Repository

This repo comprises six modules lasting from ~ 40 minutes to 2.5 hours. 

There is [module index](https://3mmarand.github.io/pgr_reproducibility/index.html)

[Seal example](https://3mmarand.github.io/pgr_reproducibility/seals/paper.html)


## Modules

1. Introduction and Principles of reproducibility  
   Audience: Everyone  
  40 mins
 
2. Introduction to R and working with data. 
   Audience: Those without previous experience  
   2 - 2.5 hr  
 
3. RStudio Projects.  
   Audience: Those without experience of RStudio projects  
   45 mins  
 
4. Tidying data and the tidyverse including the pipe.  
   Audience: For those with previous experience of R but little of 'tidy data' and the tidyverse, such as having done "Introduction to R and working with data."  
   1.5 - 2 hr  
 
5. Advanced data import.  
   Audience: For those with previous experience of R such as having done "Introduction to R and working with data" and "Tidying data and the tidyverse including the pipe."  
   2 - 2.5 hr   
 
6. R Markdown for Reproducible Reports.  
   Audience: For those with previous experience of R such as having done "Introduction to R and working with data"  
   2 - 2.5 hr 


## Materials
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">White Rose BBSRC Doctoral Training Partnership (DTP) in Mechanistic Biology Analytics 1: Introduction to reproducible analyses in R</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Emma Rand</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

Please cite as:
Rand E. (2023). White Rose BBSRC DTP Training: An Introduction to Reproducible Analyses in R (version v1.2). DOI: https://doi.org/10.5281/zenodo.3859818 URL: https://github.com/3mmaRand/pgr_reproducibility

You can obtain all the workshop materials by using the green 'Clone or download' button above.







