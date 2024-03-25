---
title: "Introduction to Reproducibility in R"
---


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3859818.svg)](https://doi.org/10.5281/zenodo.3859818)


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
-   Use Quarto to produce reproducible analyses, figures and reports


# Schedule for workshop


1015 - 1035
Tutor-led for Everyone: [Introduction and Principles of reproducibility](https://3mmarand.github.io/pgr_reproducibility/slides/01_intro_and_principles_of_repro.html)

1035 - 1200

Either: 

-   Tutor-led for Beginners:  [Introduction to R and working with data](https://3mmarand.github.io/pgr_reproducibility/slides/02_intro_to_r_and_working_with_data.html)
or
-   Supported learning for those with some R experience [Tidying data and the tidyverse including the pipe](https://3mmarand.github.io/pgr_reproducibility/slides/04_tidying_data_and_the_tidyverse.html)

1200 - 1300 Lunch 

1300 - 1330  
Tutor-led for Everyone: [Project-oriented workflow](https://3mmarand.github.io/pgr_reproducibility/slides/03_rstudio_projects.html)

1330 - 1445  
Tutor-led for Everyone: [Quarto for Reproducible Reports](https://3mmarand.github.io/wr-analytics-1/modules/quarto/slide.html#/title-slide)

1515 - 1515 Tea and coffee break 

1515 - 1645  
Continuation Quarto for Reproducible Reports



# Pre-course instructions for participants

## Precourse survey

To help me direct you to useful training and manage diversity in previous experience during the sessions, please complete this form to indicate your current level: https://forms.gle/cpSjdcjVa7niz6iq5

# Computing requirements

If you decide to use your own laptop, please install the following **before** 
the workshop. If you have any problems with installation, please use the 
computers provided at the venue.


-   R version R-4.3. https://cloud.r-project.org/

-   RStudio Desktop (1.4) https://posit.co/download/rstudio-desktop/

-   OS-specific development tools:
    -   Windows: Rtools https://cran.r-project.org/bin/windows/Rtools/
    -   Mac: Xcode https://developer.apple.com/xcode/

-   these packages: **`devtools`**, **`tidyverse`**, **`janitor`**
    Once you have installed R and RStudio, start RStudio and go to the 
    Packages tab in the bottom right pane; click Install and type the 
    name of the package you want to install in the box that appears. 
    Then wait until you get the cursor (>) back in the console window
    and install the next package.

-   Quarto https://quarto.org/

-   TinyTeX
    Use the Terminal (lower left, behind the console) in RStudio and type
    `quarto install tinytex`
    then enter.

## Materials

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">White Rose BBSRC Doctoral Training Partnership (DTP) in Mechanistic Biology Analytics 1: Introduction to reproducible analyses in R</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">Emma Rand</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.

Please cite as:
Rand E. (2023). White Rose BBSRC DTP Training: An Introduction to Reproducible Analyses in R (version v1.2). DOI: https://doi.org/10.5281/zenodo.3859818 URL: https://github.com/3mmaRand/pgr_reproducibility

You can obtain all the workshop materials by using the green 
'Clone or download' button above.







