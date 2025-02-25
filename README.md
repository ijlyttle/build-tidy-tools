# [Building tidy tools](https://rstudio-conf-2022.github.io/build-tidy-tools)

### rstudio::conf 2022

by Emma Rand + Ian Lyttle

------------------------------------------------------------------------

INSTRUCTIONS FOR INSTRUCTORS: Please insert information about your workshop below. Then, add workshop content in the materials folder and link to each session’s materials from the schedule below. You are welcomed to add more rows to the schedule. We just ask that you take breaks at the specified times. Once you are done adding information, you can remove these instructions from the README.

------------------------------------------------------------------------

🗓 July 25 and 26, 2022  
⏰ 9:00 - 17:00  
🏨 [ADD ROOM]  
✍️ [rstd.io/conf](http://rstd.io/conf)


------------------------------------------------------------------------

## Overview

This is a two-day, hands-on workshop for those who have embraced the tidyverse and want to build their own packages. We’ll discuss how functions present to the user, functional programming tools, and Object-oriented programming with S3 (R's simplest system of OOP). We will also cover the tidy eval system which allows you to use tidyverse grammar in your functions.

-   Learn efficient workflows for developing high-quality R functions, using the set of conventions codified by a package. You’ll also learn workflows for unit testing, which helps ensure that your functions do exactly what you think they do.
-   Master the art of writing functions that do one thing well and can be fluently combined together to solve more complex problems. We’ll cover common function writing pitfalls and how to avoid them.
-   Learn how to write collections of functions that work well together, and adhere to existing conventions so they’re easy to pick up for newcomers.

You should take this workshop if you have experience programming in R and want to learn how to tackle larger scale problems. You’ll get the most from it if you’re already familiar with functions and are comfortable with R’s basic data structures (vectors, matrices, arrays, lists, and data frames).

## Learning objectives

[ADD AN ITEMIZED LIST OF LEARNING OBJECTIVES.]

## Is this course for me?

Have you written a few of your own R functions? Are you ready to start sharing your code (or data) through R packages? Are you curious what you can do to make your first R packages easy for your users to use, and for you to maintain?

## Prework

To get the most out of this workshop you will need a laptop with the following installed:

- R and RStudio

- R package development toolchain: Rtools(windows) or XCode (mac) or r-base-dev

- The following packages: `devtools` and TO ADD WHEN FINALISED

- Git

- GitHub account

- GitHub to be linked to RStudio

Detailed instructions for installing these are covered in [Prerequisites](https://rstudio-conf-2022.github.io/build-tidy-tools/materials/pre-reqs.html)

## Schedule

### Day 1

| Time          | Activity       |
|:--------------|:---------------|
| 09:00 - 10:30 | [Session 1: Introduction and the whole game](https://rstudio-conf-2022.github.io/build-tidy-tools/materials/day-1-session-1-introduction.html) |
| 10:30 - 11:00 | *Coffee break* |
| 11:00 - 12:30 | [Session 2: Documentation - Minimal](https://rstudio-conf-2022.github.io/build-tidy-tools/materials/day-1-session-2-doc-minimal.html)     |
| 12:30 - 13:30 | *Lunch break*  |
| 13:30 - 15:00 | [Session 3: Unit testing]((https://rstudio-conf-2022.github.io/build-tidy-tools/materials/day-1-session-3-testing.html)) |
| 15:00 - 15:30 | *Coffee break* |
| 15:30 - 17:00 | [Session 4: Documentation - Sharing](https://rstudio-conf-2022.github.io/build-tidy-tools/materials/day-1-session-1-doc-sharing.html)  |

### Day 2

| Time          | Activity       |
|:--------------|:---------------|
| 09:00 - 10:30 | Session 1      |
| 10:30 - 11:00 | *Coffee break* |
| 11:00 - 12:30 | Session 2      |
| 12:30 - 13:30 | *Lunch break*  |
| 13:30 - 15:00 | Session 3      |
| 15:00 - 15:30 | *Coffee break* |
| 15:30 - 17:00 | Session 4      |

## Instructors

Emma Rand is a Senior Lecturer (Associate Prof) in the Department of Biology at the University of York where she specialises in teaching data science and reproducibility, particularly to those who do not see themselves as programmers. She leads a UKRI funded project called Cloud-SPAN which trains researchers in cloud-based high performance computing for 'omics. She is a Software Sustainability Institute Fellow, a Teaching team lead for R Forwards and delivers data science training for the Royal Society of Biology and the Biochemical Society.

Ian Lyttle is a Data Scientist at Schneider Electric. His technical interests include visualization, interactivity, and functional programming. He is a community contributor to tidyverse and r-lib, and maintains CRAN packages including vegawidget and boxr. He has delivered tutorials on a variety of R topics at UseR!, Uncoast Unconf, and the Iowa State University Graphics Group.

------------------------------------------------------------------------

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
