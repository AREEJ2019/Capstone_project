# Capstone_project

# Project: Capstone Project - (New York City Current Job Postings _ Kaggle Data)
Areej Albishi
Date: Nov 4, 2017
## Table of Contents

<ul>
<li><a href="#Installation">Installation</a></li>
<li><a href="#Project Motivation">Project Motivation</a></li>
<li><a href="#Data preparation and clean">Data preparation and clean</a></li>
<li><a href="#File Description">File Description</a></li>
<li><a href="#Results">Results</a></li>
<li><a href="#Licensing, Authors, and Acknowledgements">Licensing, Authors, and Acknowledgements</a></li>
</ul>


<a id='Installation'></a>
# Installation
The code should run with no issues using Python versions 3.*.
<a id='Project Motivation'></a>

# Project Motivation
Job opprtunities is very importrnt in each country , new york consider one of the most crowded cities. people are alwayes looking for jop opprtunities to live in this nice city and for that this dataset that available in kaggele by Department of Citywide Administrative Services (DCAS) will help us to understand the jobs poitions by answering some questions. "This dataset contains current job postings available on the City of New York’s official jobs site (http://www.nyc.gov/html/careers/html/search/search.shtml). Internal postings available to city employees and external postings available to the general public are included.the dataset is hosted by the City of New York. The city has an open data platform found(https://opendata.cityofnewyork.us/) and they update their information according the amount of data that is brought in. Explore New York City using Kaggle and all of the data sources available through the City of New York organization page! This dataset is updated weekly."

"This project will follow the CRISP-DM process (Cross Industry Process for Data Mining)
In this project, will focus to answer this 4 questions:
- What is the top job posting Agencies in New York City? 
- What is the Top Business Title needed in New York?
- Does most agencies offer Full_Time or Part_Time of job posting in New York?
- What kind of Business Title in new york offerd highest number of job position ?

<a id='Data preparation and clean'></a>
# Data preparation and clean
Data is checked using some functins ,missing values ,duplicates and drop some cloumns that wont be used in the analysis.
first i checked the data duplicates and found 23 duplicated recored and i droped them ,then i droped the cloumns ['INCIDENT_NUMBER','OFFENSE_CODE', 'OFFENSE_CODE_GROUP', 'DISTRICT','REPORTING_AREA','SHOOTING','UCR_PART','STREET','Lat','Long','Location'] since it wont be needed in analysis based on my questions. after that i checked if there is  null value in data and there was no nulls .
  

<a id='File Description'></a>
# File Description

These are the following files I used to complete this analysis:
Capstone_job_Posting.ipynb: The iPython notebook containing all calculations, figures, and findings pertaining to the project.
job_Posting.html: html containing all calculations, figures, and findings pertaining to the project.
nyc-jobs.csv: A file containing all of the dates available for crime in Boston


<a id='Results'></a>
# Results
The main findings of the code can be found at the job_Posting.html or Capstone_job_Posting.ipynb that provided in the git hub repository



<a id='Licensing, Authors, and Acknowledgements'></a>

# Licensing, Authors, and Acknowledgements

thanks to Udacity courses for some of code ideas, and to kaggle/New York City Current Job Postings for the data. You can find the Licensing for the data and other descriptive information at the Kaggle link available here <a href="https://www.kaggle.com/new-york-city/new-york-city-current-job-postings">Kaggle</a>. Otherwise, feel free to use the code here as you would like!
