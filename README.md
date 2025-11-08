# Data-Analysis-on-Olympics
# Olympic Athletes Data Analysis

This Jupyter Notebook contains an exploratory data analysis of Olympic athletes data from the `olympics.csv` dataset. The analysis focuses on understanding the structure, distribution, and characteristics of Olympic athletes across different dimensions.

## Dataset Overview

The dataset contains information about Olympic athletes with the following columns:
- **ID**: Unique identifier for each athlete
- **Name**: Athlete's name
- **Sex**: Gender (M/F)
- **Age**: Athlete's age
- **Height**: Athlete's height
- **Weight**: Athlete's weight
- **Team**: Country/team name
- **NOC**: National Olympic Committee code
- **Games**: Olympic games edition
- **Year**: Year of competition
- **Season**: Summer or Winter Olympics
- **City**: Host city
- **Sport**: Sport category
- **Event**: Specific event
- **Medal**: Medal won (Gold/Silver/Bronze/NaN)

## Key Analysis Steps

### 1. Data Loading and Initial Exploration
- Imported necessary libraries (pandas, matplotlib, seaborn, numpy)
- Loaded the dataset containing 70,000 entries
- Examined basic statistics and data structure

### 2. Data Quality Assessment
- Identified missing values in Age (2,732), Height (16,254), Weight (17,101), and Medal (60,310) columns
- Removed 383 duplicate records

### 3. Visual Analysis

#### Gender Distribution
- Created a count plot showing the distribution of athletes by gender
- Majority of athletes are male (51,877) compared to female (18,123)

#### Age Distribution
- Generated a histogram with KDE to visualize the age distribution of athletes
- Most athletes are in their early to mid-20s, with a peak around age 25

## Notable Findings

- **Most Frequent Athlete**: Oksana Aleksandrovna Chusovitina appears 29 times in the dataset
- **Top Team**: United States has the most athletes (4,979)
- **Most Common Sport**: Athletics (10,629 participants)
- **Recent Dominance**: 2016 Summer Olympics has the most entries (3,675)
- **Popular Event**: Football Men's Football appears most frequently (1,738 times)

## Technical Details

The analysis uses:
- Python data science stack (pandas, numpy, matplotlib, seaborn)
- Data cleaning and preprocessing techniques
- Statistical summaries and visualizations
- Handling of missing values and duplicates

This analysis provides foundational insights into Olympic athlete demographics and participation patterns, which could be extended with more detailed statistical modeling and trend analysis across different Olympic editions.
