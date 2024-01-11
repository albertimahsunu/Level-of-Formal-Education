# Nigeria-Population
![](https://assets.ourworldindata.org/uploads/2021/12/Population-cartogram_World-800x306.png)

## Introduction

This project shows the various attributes of Populations Data ranging from 2012 to 2016. 
There have been lots of bants in the data community about understanding the population dynamics and I find it interesting everytime I pump on those conversations.
The goal is to use this dataset to answer some questions.
I hope you enjoy going through this project as much as I did working on it. 😊✨

*N.B: this project does not give an exhaustive or definite analysis. Region, and company can be a factor to vary from the findings we have here.*

## Data Sourcing
The dataset was gotten from DataBank.WorldBank is linked [here](https://databank.worldbank.org/source/jobs).

## Problem Statement
The following questions were answered based on how the data was transformed:

1. The job title with the highest salary - (My favourite part😁)
2. Gender with the highest respondent - (yeah, you guessed right😎)
3. Country of resident of respondents
4. Favourite programming language
5. Difficulty to break into the space
6. Level of happiness with Salary and Work/life balance.

## Data Transformation

The dataset came really messy and required a good time of data transformation.
It has 28 columns and 630 rows.
All the cleaning was done on Power Query but was imported as a CSV file. 
The following issues:
- Missing values
- Data redundancy
- Inconsistencies
- Empty columns


Empty columns            |   Column headers
:-----------------------:|:-----------------:
![](Empty_cells_for.JPG)   | ![](Rename_headers.JPG)
- Inaccurate entries
I renamed a few column headers as they were too long and entries were inapporpriate.
Split some columns by delimiter to remove entries that would not be used for the analysis.
 

## Skills/Concepts used

To get some columns for visualization and storytelling, I created new measures.
used DAX, and filters.

## Data Modelling
No modelling was done in this project as there was just one table.

## Analysis and Visualization
![](New_dashboard.JPG)

**You can interact with the dashboard [here](https://app.powerbi.com/view?r=eyJrIjoiZjA3MDY4NzYtM2JhMi00OWZmLTkxNDktNDVjOWRlYmRmMjQ3IiwidCI6IjhjNmEzZDFhLWY5N2ItNDBjMC05ZTgxLTMxYzEwOTQxMzU3NiJ9)**

From the dashboard, we see that
1. There were 630 total respondents that filled the survey with a whooping 74% male and 24% female respondents - *This is a call for more women into the data profession.😀*
2. The average age of respondents, when rounded up is 30 years.
3. Some people are not happy with their current salary because it shows a scale of below 5.
4. A little above 5 for the work/life balance happiness.
5. Most of the population is from the United States with 261 respondents.
6. Most professionals found it neither difficult nor easy to penetrate into the space.
7. It is quite amazing to see that Python is the most loved programming languauge.
8. The highest paid job title is the **Data Scientist**...🤯🤯


## Final Thoughts🧨

- Data professionals are not exactly happy with their salary and truth is they do a whole lot of work. I strongly suggest that increment of salary is of importance.
- The percentage of women in the data space is really minute and women need to come into the space a whole lot more.
- Most professionals do not consider SQL as a programming language, I find this to be bias because every role in the data space cannot exactly to some extent, survive without SQL. There were a few SQL entries from the dataset but it was identified as "Others".

![](courtney-hedger-t48eHCSCnds-unsplash.jpg)

#### Thank you for reading through!👊🏽🤝🏽
