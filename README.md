# Data-Science-Job-Posting-on-Glassdoor



### Project Overview

This project involves analyzing data science job postings from Glassdoor to extract insights about salary trends, skills requirements, industry demand, and more. The project is split into two parts:

**Data Cleaning:** Custom methods were applied to clean the raw dataset

**Data Analysis:** The cleaned dataset were used for exploratory analysis.


### Datasets
The project utilizes two datasets:

**Raw Dataset** (Uncleaned_DS_jobs.csv): Uncleaned job postings scraped from Glassdoor.

**Cleaned Dataset** (Cleaned_DS_Jobs.csv):Provided by the data author for direct analysis.

### Key Data Fields
- **Job Info:** Title, Description, Salary Estimate (min/max/avg), Company, Location, Industry, Sector, Revenue.
- **Skills**: Python, Excel, Hadoop, Spark, AWS, Tableau, Big Data, etc.
- **Additional:** Company Age, Headquarters, Type of Ownership, etc.



## Analysis Steps
**Data Cleaning:** Handled missing values, standardized formats, extracted features (like company name, salary estimator, and location).

### Part 2: Data Analysis:
- Job Title & Salary Distribution
- Skill & Industry Demand
- Top job titles across industries
- Visualization using bar charts, pie charts, heatmaps, and more.

**Note:** Some visualizations were created using Plotly, which may not render interactively on GitHub. To view interactive charts, you can open the Jupyter Notebook locally or on platforms like [nbviewer](https://nbviewer.org/) or [Google Colab](https://colab.research.google.com/)
.

### Key Insights
- **High Demand:** Data Scientist roles are in the highest demand, particularly in the tech industry.
- **Location:** Most companies are headquartered in the USA, especially in California.
- **Ownership:** 58.5% of companies are privately owned.
- **Skills in Demand:** Python, often combined with Excel, Spark, or AWS, is highly sought after.
- **Company Age:** Only a few companies are over 150 years old, but most have grown in the last 50 years.
- **Top Salaries:** Computer Scientist, Field Application Scientist, and Senior Principal Data Scientist roles have the highest average salaries.
  
### Installation
To run this project, you need:
- Python 3.x, Jupyter Notebook, and the following libraries: pandas, numpy, matplotlib, seaborn, plotly.

### Conclusion
This analysis provides a comprehensive understanding of the current data science job market, highlighting key job titles, required skills, Industries, and salary trends.


**Dataset Source**
The original dataset used in this analysis can be found on [Here](https://www.kaggle.com/datasets/rashikrahmanpritom/data-science-job-posting-on-glassdoor/data), provided by Rashik Rahman on Kaggle.



