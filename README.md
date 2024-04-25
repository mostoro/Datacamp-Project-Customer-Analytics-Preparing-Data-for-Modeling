# Datacamp-Project-Customer-Analytics-Preparing-Data-for-Modeling


## Overview
This dataset, `customer_train.csv`, contains anonymized information of students enrolled with Training Data Ltd., an online data science training provider. The dataset is designed for the development of predictive models to determine whether students are seeking new job opportunities. This information helps in directing them to prospective recruiters.

## Dataset Description
The dataset includes the following columns:

- **student_id**: Unique identifier for each student.
- **city**: Code representing the city where the student resides.
- **city_development_index**: A scaled index representing the level of development of the student's city.
- **gender**: The gender of the student.
- **relevant_experience**: Indicator of whether the student has relevant work experience.
- **enrolled_university**: Type of university course the student is enrolled in.
- **education_level**: The highest level of education attained by the student.
- **major_discipline**: The main field of study of the student.
- **experience**: Total years of work experience.
- **company_size**: Number of employees at the student's current employer.
- **last_new_job**: Number of years since the student's last new job.
- **training_hours**: Total hours of training completed by the student.
- **job_change**: Indicator whether the student is looking for a new job (`1` for yes, `0` for no).

## Objective
The primary objective of this dataset is to facilitate the creation of a machine learning model to predict job-seeking behavior of students. This prediction can enhance the efficiency of connecting students with potential recruiters.

## Data Usage
1. **Data Cleaning**: Initial cleaning to handle missing values and outliers.
2. **Data Transformation**: Convert categorical data into a format suitable for modeling.
3. **Feature Engineering**: Derive new features that might improve model's performance.
4. **Model Development**: Use the dataset to train models that predict the likelihood of students seeking new job opportunities.

## File Format
The dataset is stored in CSV format, which can be accessed and manipulated using standard data processing tools in Python, R, or any other data analysis software.

## Usage Policy
The data is anonymized and shared for educational purposes. Users are required to use this dataset only for non-commercial purposes and are advised to keep it confidential.
