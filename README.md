### Table of Contents
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Data](#data)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
This project was developed using Python version 3.6.0.
Other requirements can be found in `requirements.txt`.

## Project Motivation<a name="motivation"></a>
The main purpose of this project is to explore at some key aspects of the data and their evolution in the past 
years(2017-2020), and comparing the trends for Europe versus the rest of the world. 
Here Europe stands for countries belonging to the European Union.
1. How did the interest in this survey has evolved over time?
2. How did the interest in programming languages /frameworks/platforms has evolved over time?
3. How has the salary evolved over time?
4. What were some interesting survey questions over the years?

## Data<a name="data"></a>
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
## File Descriptions <a name="files"></a>
.
├── LICENSE
├── README.md
├── SO\ Survey\ -\ Europe\ vs\ the\ world\ data\ analysis.ipynb
└── requirements.txt

The solution for the above questions can be found in SO\ Survey\ -\ Europe\ vs\ the\ world\ data\ analysis.ipynb file.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@ioana.grigoropol/europe-versus-the-world-a-developers-view-18914262220c).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the data.  
Licensing for the data can be found [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).
The code provided here is under GNU GENERAL PUBLIC LICENSE.