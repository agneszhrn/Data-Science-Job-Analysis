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
- Removed unwanted columns: 'Unnamed: 0'
![image](https://user-images.githubusercontent.com/67780196/179521649-c01d4bed-bbda-4fad-84c0-9b4a8b9a7808.png)

- Checking and handling missing values
![image](https://user-images.githubusercontent.com/67780196/179521917-8cb57e51-6e5d-4fb3-99a5-a3447f0c27a3.png)


- Checking duplicated data
![image](https://user-images.githubusercontent.com/67780196/179522067-0b1d6029-3cf2-4ebf-805d-2f56b54b280b.png)
There are 42 duplicate rows; will be dropped using the `df.drop()` function.
