# Data-Science-Job-Analysis
According to the 2020 LinkedIn U.S. Emerging Jobs Report,  data science has experienced continued growth on a tremendous scale in recent years. Across nearly every industry, organizations are competing for data science professionals to leverage their data and drive smart business decisions. However, since the supply of data professionals has not yet caught up with the demand, the competition between companies in hiring these professionals is fierce compared to in other tech sectors. As a result, employers are willing to pay top salaries to talented data scientists.

Notwithstanding the profitable honeymoon this field is experiencing, it is important to note that the data science salaries can range considerably across professionals. Employers take into account several factors when deciding how much to pay, including experience, skills, job title, or company size. 

## Linkdin Profile
For any queries regarding about this project contact me.
Link : https://www.linkedin.com/in/agneszahrani/

## Acquisition of data
The Data Science salary data (Salary_Data.csv) that we will use for the analysis is obtained from Kaggle.
Link : https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries?resource=download

## Dataset
![image](https://user-images.githubusercontent.com/67780196/179521118-9718c228-960f-45d8-9f26-edf1dd911c84.png)
The dataset consists of 12 columns and 607 rows.
- Unnamed: 0
- work_year
- experience_level
- employment_type
- job_title
- salary
- salary_currency
- salaryinusd
- employee_residence
- remote_ratio
- company_location
- company_size

## Data Cleansing
• Removed unwanted columns: 'Unnamed: 0'.

• Dataframe has no missing values.

• Drop 42 duplicate rows found.

• Renaming the column value
- experience_level : EN = Entry-level, MI = Mid-level, SE = Senior-level, EX = Expert-level
- employment_type : PT = Part-time, CT = Contract, FT = Full-time, FL = Freelance
- remote_ratio.replace : 0 = Onsite, 50 = Hybrid, 100 = Remote
- company_size.replace : S = Small, M = Medium, L = Large

## Exploratory Data Analysis (EDA)
### Creating boxplot to see outliers in data.

![image](https://user-images.githubusercontent.com/67780196/179526960-c8e5132f-cfb6-4d97-9694-914ecba4509b.png)

Obervations:
- There is no outlier in work_year column.
- There are some outliers in the salary and salary_in_usd columns.

### Analysis 1: What is job with the highest salary in Data Science?
![image](https://user-images.githubusercontent.com/67780196/179528318-1b4627e5-4184-4298-9188-7d1363a72b36.png)

Observations:
- 

### Analysis 2: What are the top 10 data science jobs in 2022?
![image](https://user-images.githubusercontent.com/67780196/179528586-4ab569cb-2bba-4e05-a55f-bc4614e89d85.png)

Observation:
- In 2022, the top 10 popular data science jobs are shown on the chart and the most popular is Data Engineer.

### Analysis 3: How does the remote-ratio vary from year 2020 -2022?
![image](https://user-images.githubusercontent.com/67780196/179528792-8b928ab2-279b-41a0-a764-61654bd6fa93.png)

Observations:
- From 2020 to 2022 there will be an increase in the rate of remote work by Data Science workers.
- The chart shows the existence of a new culture that is most favored by Data Science workers, namely remote / work from home.
