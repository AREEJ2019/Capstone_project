# Capstone_project

# Project: Capstone Project - (New York City Current Job Postings _ Kaggle Data)
Areej Albishi
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
Job opportunities is very important in each country , new York consider one of the most crowded cities. people are always looking for job opportunities to live in this nice city and for that this dataset that available in kaggle by Department of Citywide Administrative Services (DCAS) will help us to understand the jobs positions by answering some questions. "This dataset contains current job postings available on the City of New York's official jobs site (http://www.nyc.gov/html/careers/html/search/search.shtml). Internal postings available to city employees and external postings available to the general public are included. The dataset is hosted by the City of New York. The city has an open data platform found(https://opendata.cityofnewyork.us/) and they update their information according the amount of data that is brought in. Explore New York City using Kaggle and all of the data sources available through the City of New York organization page! This dataset is updated weekly."

"This project will follow the CRISP-DM process (Cross Industry Process for Data Mining)
In this project, will focus to answer this 4 questions:
1.  What is the top job posting Agencies in New York City? 
2.  What is the Top Business Title needed in New York?
3.  Does most agencies offer Full_Time or Part_Time of job posting in New York?
4.  What kind of Business Title in new york offerd highest number of job position ?

<a id='Data preparation and clean'></a>
# Data preparation and clean
Data is checked using some functions ,missing values ,duplicates and drop some columns that wont be used in the analysis. rename the column. i checked the data duplicates and i dropped them ,then i dropped the columns that wont be nodded in analysis based on my questions. after that i checked the null values and performed one-hot encoding on categorical columns like Full_Time and Part_Time of job posting indicator
  

<a id='File Description'></a>
# File Description
the notebook available here showcases work related to the above questoins.
the dataset siplified vesion of the real New York City Current Job Postings
These are the following files I used to complete this analysis:
- `Capstone_job_Posting.ipynb:`The iPython notebook containing all calculations, figures, and findings pertaining to the project.
- `job_Posting.html:` html containing all calculations, figures, and findings pertaining to the project.
- `nyc-jobs.csv:` A file containing all of the dates available for job posting in NY

Here is aschema and explanation of each varible in the nyc-jobs.csv file:
 `nyc-jobs.csv:`
- Job ID(ID):offer id
- Agency(string): the type of Agencys that posting jobs ie DEPT OF ENVIRONMENT PROTECTION,NYC HOUSING AUTHORITY
- Posting Type(string): the type of posting  Internal postings available to city employees and external postings available to the general public 
- '# Of Positions(intger):' number of job posting offered from each agencyies.
- Business Title(string): the Title of job offering ie Assistant Civil Engineer,Project Manager
- Civil Service Title (string): type of Civil Service Title ie COMMUNITY COORDINATOR,AGENCY ATTORNEY,CIVIL ENGINEER
- Title Code No(string): the title code nnumber(id) 
- Level(String): level of job posting 4 levels(0,1,2,3,4)
- Job Category(string): type of Job Category ie Engineering, Architecture, & Planning or Technology, Data & Innovation
- Full-Time/Part-Time indicator(String): F represent Full time job offering and P represent part time job offering.
- Salary Range From(Decimal): slalary rang for job offfering.
- Salary Range To(Decimal): stalary range rach to 
- Salary Frequency(String): slary frequacy if its annual bases or daily or Hourly base.
- Work Location(String): locations for job posting ie 96-05 Horace Harding Expway,59-17 Junction Blvd Corona Ny
- Division/Work Unit(string):divisions of job offering ie Executive Management,Central Brookly City Operation
- Job Description(string): job describtion
- Minimum Qual Requirements: mininumm qualification required ie  A baccalaureate degree from an accredited college and two years of experience in community work or community centered activities in an area related to the duties described above; or 2. High school graduation or equivalent and six years of experience i.
- Preferred Skills(string): skilled most prefferd in job posting ie Ability to communicate effectively in verbal and written form.
- Additional Information(string): adddtional info about job offered ie NYCHA employees applying for promotional, title or level change opportunities must have served a period of one year in their current title and level (if applicable).
- To Apply(string): represent the apply for the job ie Click the "Apply Now" button.
- Hours/Shift(string): number of hours or shifts with job ie 35 hours per week
- Work Location 1(string): place locations ie 30-30 Thomson Avenue, LIC, NY
- Residency Requirement(string): requirment for residency if their is any  ie New York City Residency is not required for this position,New York City residency is generally required within 90 days of appointment. However, City Employees in certain titles who have worked for the City for 2 continuous years may also be eligible to reside in Nassau, Suffolk, Putnam, Westchester, Rockland, or
- Posting Date(date): date of job posting.
- Post Until(date) : date of job posting ends.
- Posting Updated(date): any date updates.
- Process Date(date) ; processing dates of the job applying.







<a id='Results'></a>
# Results
he main findings of the code can be found at the post available [here](https://medium.com/@albishiareej/project-data-science-capstone-project-job-posting-in-usa-ny-162cfb9b972c).

<a id='Licensing, Authors, and Acknowledgements'></a>

# Licensing, Authors, and Acknowledgements

thanks to Udacity courses for some of code ideas, and to kaggle/New York City Current Job Postings for the data. You can find the Licensing for the data and other descriptive information at the Kaggle link available here <a href="https://www.kaggle.com/new-york-city/new-york-city-current-job-postings">Kaggle</a>. Otherwise, feel free to use the code here as you would like!
