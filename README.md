# Google Careers Job Listings Analysis

## Project Overview

This project focuses on scraping and analyzing job listings from Google Careers.

The data was collected from multiple Google Careers Jobs Results pages using Python, Requests, and BeautifulSoup. The collected data contains information about job titles, company, location, and experience level.

The scraped data was cleaned, explored, visualized, and statistically analyzed to identify patterns and relationships within the job listings.

---

## Business Problem

Google Careers contains a large number of job listings across different locations and experience levels. Analyzing these listings manually can be difficult.

This project aims to organize and analyze the job listing data to understand the distribution of job opportunities across locations, job titles, and experience levels.

---

## Project Objective

- Scrape job listing data from Google Careers.
- Collect job title, company, location, and experience level.
- Clean and organize the collected data.
- Perform exploratory data analysis.
- Analyze relationships between categorical variables.
- Apply statistical analysis to identify significant associations.
- Generate meaningful insights from the scraped data.

---

## Data Collection

The job listings were scraped from the Google Careers Jobs Results pages using:

- Python
- Requests
- BeautifulSoup

The scraping process collected the following fields:

- Job Title
- Company
- Location
- Experience Level

The data was collected from multiple pages of the Google Careers job listings.

---

## Dataset

The final dataset contains:

- **3,338 job listings**
- **4 columns**

### Columns

| Column | Description |
|---|---|
| `job_title` | Title of the job position |
| `company` | Company associated with the listing |
| `location` | Location of the job |
| `experience_level` | Experience category of the job |

### Experience Levels

- Early
- Mid
- Advanced
- Director+
- Intern & Apprentice

---

## Data Cleaning

The following data-cleaning steps were performed:

- Checked for missing values.
- Identified and removed duplicate records.
- Checked data types.
- Reviewed categorical values for inconsistencies.
- Verified the cleaned dataset before analysis.

---

## Exploratory Data Analysis

EDA was performed to understand the distribution of job listings.

The analysis included:

- Distribution of job postings by experience level.
- Top job locations.
- Most frequently occurring job titles.

Python libraries such as Matplotlib and Seaborn were used to create visualizations.

---

## Bivariate Analysis

Relationships between categorical variables were analyzed using:

- Location × Experience Level
- Job Title × Experience Level
- Location × Job Title

Count plots and other visualizations were used to compare these variables.

---

## Statistical Analysis

The **Chi-Square Test of Independence** was applied to examine associations between categorical variables.

The analysis used the **p-value** to determine whether the observed associations were statistically significant.

---

## Key Insights

- Mid-level positions represent a large portion of the job listings.
- Advanced-level positions also account for a substantial number of listings.
- Google Careers contains job opportunities across a wide range of locations.
- A wide variety of job titles are present in the dataset.
- Statistical analysis was used to examine relationships between job title, location, and experience level.

---

## Tools & Technologies

- Python
- Requests
- BeautifulSoup
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Regular Expressions
- Jupyter Notebook

---

## Project Workflow

**Business Problem → Data Collection → Data Understanding → Data Cleaning → EDA → Bivariate Analysis → Statistical Analysis → Insights → Conclusion**

---

## Source

**Website:** Google Careers – Jobs

The job listings were collected from the Google Careers Jobs Results pages.

---

## Project Files

- `Google_careers_webscrapping.csv` — Cleaned dataset
- `Google_Careers_Web_Scraping.ipynb` — Web scraping, cleaning, and analysis notebook
- `README.md` — Project documentation

---

## Conclusion

This project demonstrates an end-to-end workflow for collecting real-world job listing data through web scraping and transforming it into structured data for analysis.

The project combines **web scraping, data cleaning, exploratory data analysis, visualization, and statistical analysis** to understand patterns within Google Careers job listings.
