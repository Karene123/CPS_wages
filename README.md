# LABOR FORCE PARTICIPATION BASED ON 

<!-- PROJECT LOGO -->
<br />
  <a href="https://github.com/Karene123/CPS_wages">
    <img src="https://github.com/Karene123/ESG-Project/assets/70621033/26b3a4fd-b7a9-4385-b2d9-49475c08ce96" alt="Logo" width="1500" height="500">
  </a>
  
<!-- TABLE OF CONTENTS -->
### Table of Contents

1. [Project Overview](#Project-Overview)
2. [Getting Started](#Getting-Started)
3. [Prerequisites](#Prerequisites)
4. [Utilized Python Libraries](#Utilized-Python-Libraries)
5. [Installation](#Installation)
6. [Challenges](#Challenges)
7. [Summary of Results and Methods Used](#Summary-of-Results-and-Methods-Used)
8. [Contributions](#Contributions)
9. [Acknowledgments](#Acknowledgments)
10. [Graphs](#Graphs)

# Environment, Social, and Government Data (ESG) from the World Bank Data Bank

<!-- Project Overview -->
## About The Project

The Integrated Public Use Microdata Series (IPUMS) has been providing a collection of data extracted from sixty surveys. This collection is recognized as having the most complete and richest quantifiable data on long-term changes in the American Population (Team, M. U. (n.d.)). Utilizing this website, a labor market analysis will be conducted followed by a data manipulation task. We will be working on two distinct datasets for each task. The first comes from the US Current Population Survey and the second involves Medicare. The goal of this analysis is to explore how hourly wages and labor force participation progressed since 1976 depending on whether or not the worker was skilled. To offer an answer to this question, we will be exploring the trends for wages and labor force participation. Then, we will further analyze the groups of people who had the biggest changes in labor force participation. We will conclude by analyzing the potential factors that led to those patterns.

Exploring the American Labor Market starting from 1976 with the following variables:
-   `Year` indicates the year involved.
-   `Statefip`indicates the state involved.
-   `Month` indicates the month involved.
-   `Wtsupp`
-   `Age` includes the age included.
-   `Sex` includes the sex included.
-   `Race` includes the race included.
-   `Hispanic`
-   `Educ` includes the level of education.
-   `Empstat` indicates whether the respondent was a part of the labor force
-   `Occ` indicates occupation codes
-   `Wkswork1` reports the number of weeks that the respondent worked for profit, pay, or as an unpaid family worker during the previous year.
-   `Wkswork2` reports the number of weeks that the respondent worked for profit, pay, or as an unpaid family worker during the previous year.
-   `Uhrswork` reports the number of hours per week that the respondent usually worked, if the person worked during the previous year.
-   `Inctot` reports each respondent's total pre-tax personal income or losses from all sources for the previous year.
-   `Incwage` reports each respondent's total pre-tax wage and salary income - that is, money received as an employee - for the previous year.
-   `Age_group`
-   `White`
-   `Skilled` reports whether or not the worker is skilled.
-   `Hours` reports the number of hours worked.
-   `Wage` reports the wage.
-   `Lfp`
-   `Empstatid`

  <!-- GETTING STARTED -->
## Getting Started

This dataset was downloaded from [Predoc.org](https://predoc.org/-/media/project/chicago-booth/consortium/predoc/documents/task_overview.pdf) as part of one of their data task. I took this opporunity to perform a perform a thorough statistical analysis while answering the main research questions.

### Prerequisites

[R-4.3.2](https://cran.r-project.org/bin/windows/base/)

Install and Import those libraries in order to access the project.

### Utilized Python Libraries:

* [Dlpyr](https://dplyr.tidyverse.org/articles/dplyr.html)
* [ModelSummary](https://modelsummary.com/)
* [GGPLOT2](https://ggplot2.tidyverse.org/)
* [Egg](https://cran.r-project.org/web/packages/egg/index.html)
* [Tidyverse](https://dplyr.tidyverse.org/)
