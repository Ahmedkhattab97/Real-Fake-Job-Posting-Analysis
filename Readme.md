Real vs Fake Job Postings Analysis using Power BI

* Project Description
This project aims to analyze a dataset of real and fake job postings to identify common patterns among fraudulent jobs and distinguish them from real ones. Power BI is used to create interactive reports that visualize job distributions by location, industry, experience level, employment type, and more.

The goal is to understand the behavior of fake job postings and how they differ from genuine opportunities by examining key features in the data.

* Tools Used
- Power BI
- Excel & Power Query (for data cleaning)

* Dataset Source
The dataset is obtained from [Kaggle](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction), which contains detailed information about thousands of job postings—both real and fake.

* Key Columns in the Dataset
- `title`: Job title  
- `location`: City, state, or country  
- `department`: Department or team  
- `salary_range`: Salary offered  
- `company_profile`: Description of the company  
- `description`: Job description  
- `requirements`: Required qualifications or skills  
- `benefits`: Job benefits  
- `employment_type`: Full-time, part-time, etc.  
- `required_experience`: Years of experience required  
- `required_education`: Education level required  
- `industry`: Industry sector  
- `function`: Job function  
- `fraudulent`: Label indicating if the job is fake (1 = fake, 0 = real)

* Analysis Overview
1. Fake Jobs Page:
- Job distribution by location
- Most common departments for fake jobs
- Common employment types and experience levels in fraudulent postings

 2. Real Jobs Page:
- Most in-demand job titles and industries
- Education and experience trends
- Common job locations

 3. Comparison Page:
- Differences in departments
- Differences in employment types
- Text-based analysis of descriptions and requirements

* Key Insights
- Fake job postings often lack clear locations or provide generic ones.
- Many fake jobs have vague descriptions and no salary information.
- Certain industries (like remote marketing or tech support) appear frequently in fraudulent listings.


 How to Use
Open the provided Power BI file (`Real_vs_Fake_Jobs.pbix`) to explore the interactive dashboards and gain insights from the data.