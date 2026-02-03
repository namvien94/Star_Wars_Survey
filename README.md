# Star Wars Survey Analysis

![Star Wars Thumbnail](https://i.ytimg.com/vi/BbAzZXNrW8I/hqdefault.jpg)

## Overview
This project analyzes survey data from Star Wars fans to examine viewing habits, film rankings, and character sentiment across the franchise. Using a real-world dataset collected via SurveyMonkey and published by FiveThirtyEight, the analysis focuses on data cleaning, feature engineering, and exploratory analysis to evaluate audience preferences, including whether *The Empire Strikes Back* is the most favored film.

## Dataset
- **Source:** FiveThirtyEight Star Wars Survey  
- **Observations:** 835 survey responses  
- **Format:** CSV  
- **Key Features:**  
  - Film viewership indicators  
  - Film ranking responses  
  - Character favorability responses  
  - Demographic and fan-identification variables  

## Objectives
- Clean and standardize raw survey data with inconsistent formats  
- Transform categorical and checkbox-style responses into analyzable variables  
- Compare film rankings and viewership across the Star Wars franchise  
- Analyze audience sentiment toward major characters  

## Methodology
- Converted Yes/No survey responses into binary numeric indicators  
- Parsed multi-response checkbox columns into individual boolean variables  
- Cleaned and standardized film ranking columns for numerical comparison  
- Filtered valid responses to ensure meaningful aggregation  
- Used descriptive statistics and group-wise comparisons to summarize trends  

## Evaluation & Analysis Approach
- **Film rankings:** Calculated mean ranking scores for each film to assess relative preference.
- **Viewership analysis:** Aggregated binary viewership indicators to measure how widely each film was seen.
- **Trilogy comparison:** Compared average rankings and viewership between the original trilogy and the prequel trilogy.
- **Character sentiment:** Computed proportions of favorable, neutral, and unfavorable responses for each character to evaluate audience sentiment and polarization.

## Key Findings
- The original trilogy (Episodes IV–VI) consistently ranks higher than the prequel trilogy (Episodes I–III).
- *The Empire Strikes Back* has the strongest average ranking among all films.
- Original trilogy films show the highest viewership, reflecting enduring popularity.
- Character sentiment analysis indicates that a subset of characters consistently receives high favorable ratings.
- Some characters exhibit low favorable sentiment, suggesting weaker audience attachment.
- Several characters display polarized or predominantly neutral responses, reflecting mixed audience perceptions and varying levels of character recognition.

## Tools & Technologies
- **Python**
  - Pandas  
  - NumPy
  - Matplotlib
- **Jupyter Notebook**
