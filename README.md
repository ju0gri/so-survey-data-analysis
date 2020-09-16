# StackOverflow survey Data Analysis
This project's aim is to explore the data in the SO Survey and answer some questions.
## Business questions to answer
The main purpose of this analysis is to look at some key aspects of the data and their evolution in the past 
years(2017-2020), and comparing the trends for Europe versus the rest of the world. 
Here Europe stands for countries belonging to the European Union.
### How did the interest in this survey has evolved over time?
### How did the interest in programming languages /frameworks/platforms has evolved over time?
### How has the salary evolved over time?
### Interesting survey questions 

## Data
Data from the past years for this survey can be downloaded from: https://insights.stackoverflow.com/survey. 
The work for this exploration has been done using Jupyter Notebook, and it assumes that the data to be analysed
is located in a folder called `data/` at the root level of the project with the following structure:
```
data/
----developer_survey_2017
--------survey_results_public.csv
--------survey_results_schema.csv
----developer_survey_2018
--------survey_results_public.csv
--------survey_results_schema.csv
----developer_survey_2019
--------survey_results_public.csv
--------survey_results_schema.csv
----developer_survey_2020
--------survey_results_public.csv
--------survey_results_schema.csv
```

## Solution

The solution for the above questions can be found in project1_solution.ipynb file.

## Requirements
This project was developed using Python version 3.6.0

Other requirements can be found in `requirements.txt`.