Shark Attacks: Perception vs Reality
Project Overview
This project was developed as part of the Ironhack Data Analytics Bootcamp.
We analyzed historical shark attack records to investigate whether public perception of sharks aligns with the reality shown by data. Shark attacks are often portrayed as a widespread threat, while conservation organizations argue that public fear is disproportionate to the actual risk.
Using data cleaning, wrangling, and exploratory analysis techniques, we examined patterns in shark attack incidents and tested whether attacks are concentrated in specific activities and geographic locations.

Business Case
Client
Shark Conservation NGO
Mission
Protect shark populations and healthy ocean ecosystems by improving public understanding of sharks and supporting conservation efforts worldwide.
Business Problem
Public perception frequently portrays sharks as highly dangerous animals. This can:
Reduce support for shark conservation initiatives
Reinforce misconceptions about shark attack risk
Contribute to negative attitudes toward sharks
The NGO aims to use historical shark attack data to communicate the difference between perceived risk and actual risk.

Hypothesis
Shark attacks are concentrated in a limited number of activities and geographic areas rather than being a widespread threat.

Business Objectives
The analysis focused on answering the following questions:
Where do shark attacks occur geographically?
Which activities are most associated with shark attacks?
How often do attacks result in fatalities?
Are attacks concentrated or widespread?
What insights can support public education and conservation campaigns?

Dataset
Source
Global Shark Attack File (GSAF)
Dataset Size
7,090 historical shark attack records
Key Variables
Date
Country
Activity
Attack Type
Fatality

Methodology
1. Data Cleaning
Removed unnecessary columns
Standardized country names
Corrected inconsistent values
Handled missing data
Cleaned date fields
2. Data Wrangling
Standardized activity categories
Harmonized geographic information
Derived fatality classifications using regex-based text analysis
Created analysis-ready datasets
3. Exploratory Data Analysis (EDA)
Geographic distribution analysis
Activity frequency analysis
Fatality rate analysis
Hypothesis validation
Tools Used
Python
Pandas
Regular Expressions (Regex)
PyCountry
Jupyter Notebook
Tableau

Key Findings
Geographic Concentration
The top three countries account for approximately 73% of all recorded shark attacks.
Activity Concentration
Nearly half of all recorded attacks occurred during surfing or swimming activities.
Fatality Rates
Approximately 87% of classified shark attacks were non-fatal.
Hypothesis Result
The analysis supports the hypothesis that shark attacks are concentrated in specific activities and locations rather than representing a widespread threat.

Repository Structure
data-cleaning-pandas/
│
├── shark_attack_analysis.ipynb
├── functions.py
├── presentation_link.txt
├── README.md
└── data/


Presentation
Presentation slide link

Team
Sevgi Özdemir
Jeronimo Cagliero
Ana Preto
Ironhack Data Analytics Bootcamp June 2026
