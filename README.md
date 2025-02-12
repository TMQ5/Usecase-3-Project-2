## Introduction
University rankings provide valuable insights into the global higher education landscape. This study analyzes university ranking data across **three globally recognized ranking systems**:

1. **Academic Ranking of World Universities (ARWU)** – also known as the **Shanghai Ranking**.
2. **Times Higher Education World University Rankings (THE)**.
3. **Center for World University Rankings (CWUR)**.  

### Team Members: 

1- Tahani Alotaibi 

2- Munirah Alzuman

3- Suliman Alghanmi

4- 
---

## Problem Statement 

This study aims to address the following key questions:  

1. **Which universities are ranked in the top 10 globally?**  
2. **Which universities are ranked in the top 10 based on employment outcomes?**  
3. **What is the position of Saudi universities in global rankings?**  
4. **Among factors such as employment rankings, research rankings, and academic reputation, which has the most significant impact on a university’s overall ranking?**  
5. **Is there a correlation between national and global rankings, and can we identify a country with a high concentration of top-ranked universities based on this correlation?** 

**Bonus**: Identify additional research questions that can be explored using the available dataset.

---

## Objectives 

This project aims to **analyze global university rankings** by leveraging available data to extract meaningful insights into the factors influencing university performance. The study seeks to achieve the following:  

1. **Identify top-ranked universities** across multiple ranking systems (**ARWU, THE, and CWUR**).  
2. **Assess the position of Saudi universities** within global rankings and benchmark them against leading institutions.  
3. **Analyze the influence of key factors** such as **scientific research, employment outcomes, academic awards, and citations** on ranking performance.  
4. **Evaluate the correlation between national and global rankings** to determine the consistency and reliability of various ranking methodologies.  
5. **Identify countries with the highest concentration of top-ranked universities** based on global ranking patterns.  
6. **Develop strategic recommendations** to help universities enhance their ranking performance.  
7. **Expand the analysis** by incorporating additional insights, including ranking trends over time and institutional performance shifts.  

---

## Dataset Overview and Source
We have 3 datasets for ranking universities with different methodologies, we get them from Kaggle.

1 - [Shanghai Ranking](https://www.kaggle.com/datasets/computingvictor/2024-academic-ranking-of-world-universities)

2 - [Times Ranking](https://www.kaggle.com/datasets/ddosad/timesworlduniversityrankings2024)

3 - [CWUR Ranking](https://www.kaggle.com/datasets/armanghazi/top-1000-univercity-ranking-2014-2024-cwur)

We decided to change the given datasets and collect the most current data (for the year 2024) and use it for our analysis instead, for these two reasons:

1- The problem statment questions does not specified certian time period or if they need it over the years.

2- The available datasets are not in the same period one dataset in 2022 and two datasets in 2023 and they have large number of null values that we can not handale it and will miss the inporatnat information if we delete them.


--- 

## Exploratory Data Analysis (EDA) Steps:
### 1- Data Profiling:
Here we take two steps: 

 Step1: Doing describtive analysis and get a quick sense of the datasets. 

 Step2: We checks for the 7 data quality dimension issues.
 
#### 1- Reliability

The data source is trustworthy; it comes from the Kaggle.

#### 2- Timeliness

The data provided is current and accurately represents the situation.

#### 3- Consistency

As we have different ranking methodology for each data sets so, the logical meaning of the column accept different values for the same data items.

#### 4- Relevance

- Sample Appropriateness: The data sample aligns with analysis objectives.

- Variable Selection:
  - **In Shanghai Ranking:** All the columns are important and related to our question. Just we need to add further column for universities countries.
  - **In Times Ranking:**
  - **In World University Rankings:** All the columns are related to our questions but the year column we are no longer need it after filtered the data.

#### 5- Uniqueness

Here we checked for the duplicated values. 

#### 6- Completeness

Here we checked for the Null values. 

#### 7- Accuracy

Here we checked for the data foramat and the outlier values. 

### 2- Data Cleaning:

We handle the issues that appear in the 4 dimensions (Variable Relevance, Uniqueness, Completeness, Accuracy). 

### 3- Univariate, Bivariate, Multivaiate Analysis:

Using visualization and statistics for one, two and more columns to understand their distribution and look at the relationships between variables. 

----

## Final Insights: 

1- The  almost top  10 University  in the world located in the USA that points to the strenght of the outputs of American University.

2- 

3- 

