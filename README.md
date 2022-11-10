# DA-401-Project
## Jake Caldwell

### Summary:
  This project aims to discover if there is possible correlation between the statistical production of an NBA player and how familiar people are with said player. This involves using data from BasketballRefernce.com and collecting data from a survey, using a Random Forest model to perform feature selection on two productivity statistics used by the NBA, and then comparing the top 50 most productive NBA players with the top 50 most recognized NBA players who are on the NBA 75th Anniversary Team. 

### Necessary Packages for running code in R 4.2.2
* ggalt
* vegan
* ggplot2
* ggthemes
* data.table
* dplyr
* tidyverse
* randomForest
* tidyr
* GGally
* Hmisc
* tree
* RColorBrewer
* ggvenn
* vtable
* e1071
* class
* boot

### Data Files
* (Year)SeasonStats.csv -- there are 42 of these files and each contains the season average basic statistics for each NBA player that played in that season. The range of years is from 1981-2022. 
* StudyResponses.csv -- This is a file that contains a summary of my survey data. It is deidentified and only contains the number of times each of the 50 NBA players I used were recognized and information taken from the partial order knowledge structure that determines the expertise of each respondant
* NBA.csv -- this is an aggregate table that contains all of the data from the seasonal stats files, except the players that do not meet my inclusion requirements are filtered out
* NBA75.csv -- this table contains the 50 players on the NBA 75 team that played after 1980. These are the players used in my survey. 

### Code Files
* DA401ProjCode.rmd -- this R markdown file contains all of my R code that went into the analysis on this project. 

### Supplimental Materials
* Survey.ppx -- This powerpoint is how I ran my survey's with my subjects.
* InformedConsent.pdf -- this document details my participants oral informed cosent.
* SurveyDesign.pdf -- this document outlines how my surveys are set up to run.
* Other files are supplementary writing materials (i.e. initial methods section). 
