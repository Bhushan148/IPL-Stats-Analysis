# 🏏 IPL Stats Analysis

## 📊 **Project Overview**

This project provides a deep dive into **Indian Premier League (IPL)** cricket data. It examines team performances, player statistics, and match outcomes using Python libraries. The analysis is carried out with tools such as **Pandas**, **Matplotlib**, and **Seaborn** to clean, analyze, and visualize the data, yielding actionable insights.

---

## 🔧 **Tools and Libraries**

- **Python**: The primary programming language for this analysis.
- **Pandas**: For efficient data manipulation and analysis.
- **NumPy**: For handling numerical operations.
- **Matplotlib & Seaborn**: For creating insightful data visualizations.
- **Jupyter Notebook**: For an interactive analysis experience.

---

## 📋 **Table of Contents**

1. **Data Collection and Loading**
2. **Data Cleaning and Preparation**
3. **Exploratory Data Analysis (EDA)**
    - Distribution of Match Results
    - Year-wise Runs Scored
    - Year-wise Wickets Taken
4. **Team Stats**
    - IPL Title Winners
    - Knockout Matches Appearance
    - Win Percentage in Knockout Matches
    - Greatest and Narrowest Win Margins
    - Highest Successful Chases and Team Totals
5. **Player Knockout Match Stats**
    - Most Runs and Wickets in Knockout Matches
6. **Individual Batting Records**
    - Most Career Runs
    - Highest Scores and Centuries
    - Most Career Sixes
7. **Individual Bowling Records**
    - Total Wickets Taken
8. **Fielding Records**
    - Top Fielders by Catches
9. **Match Outcomes**
    - Average Inning Scores by Venue
    - Win Margins and Toss Impact
10. **Impact of Venue and Weather Conditions**
11. **Additional Insights**

---

## 🗂 **Data Collection and Loading**

- **Data Sources**: Utilized datasets from Kaggle and official IPL statistics.
- **Loading Data**: Imported datasets into Jupyter Notebook for comprehensive analysis.

---

## 🧹 **Data Cleaning and Preparation**

- **Missing Values**: Addressed and imputed missing data entries.
- **Data Types**: Corrected data types for accurate analysis.
- **Dataset Merging**: Combined match and delivery datasets to form a unified view.

---

## 📈 **Exploratory Data Analysis (EDA)**

### 1. **Distribution of Match Results**
- Analyzed match outcomes across different seasons to identify trends.

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Distribution%20of%20Match%20Results.png" alt="Distribution of Match Results" width="60%">

### 2. **Year-wise Runs Scored**
- Examined annual runs scored to reveal performance trends over time.

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Year-wise%20Runs%20Scored.png" alt="Year-wise Runs Scored" width="60%">

### 3. **Year-wise Wickets Taken**
- Reviewed yearly wicket statistics to highlight key bowling performances.

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Year-wise%20Wickets%20Taken.png" alt="Year-wise Wickets Taken" width="60%">


---

## 📊 **Team Stats**

### 1. **IPL Title Winners**
- Identified teams with the most IPL titles, showcasing the most successful teams.

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/IPL%20Title%20Winners.png" alt="IPL Title Winners" width="60%">

### 2. **Knockout Matches Appearance**
- Ranked teams by their appearances in knockout matches, highlighting consistency.

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Knockout%20Matches%20Appearance.png" alt="Knockout Matches Appearance" width="60%">

### 3. **Win Percentage in Knockout Matches**
- Calculated win percentages to assess teams' effectiveness in high-stakes matches.

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Win%20Percentage%20in%20Knockout%20Matches.png" alt="Win Percentage in Knockout Matches" width="60%">

### 4. **Greatest and Narrowest Win Margins**
- **Greatest Win Margin (by Runs)**: Highlighted matches with the largest run margins.
  
| Margin | Winner                      | Loser                    | Venue                        | Date       |
|--------|-----------------------------|--------------------------|------------------------------|------------|
| 146 Runs | Mumbai Indians              | Delhi Daredevils         | Feroz Shah Kotla             | 2017-05-06 |
| 144 Runs | Royal Challengers Bangalore | Gujarat Lions            | M Chinnaswamy Stadium        | 2016-05-14 |
| 140 Runs | Kolkata Knight Riders       | Royal Challengers Bangalore | M Chinnaswamy Stadium        | 2008-04-18 |
| 138 Runs | Royal Challengers Bangalore | Kings XI Punjab          | M Chinnaswamy Stadium        | 2015-05-06 |
| 130 Runs | Royal Challengers Bangalore | Pune Warriors            | M Chinnaswamy Stadium        | 2013-04-23 |


- **Narrowest Win Margin (by One Wickets)**: Identified matches with the smallest wicket margins.

| Winner               | Venue                                 | Date       |
|----------------------|---------------------------------------|------------|
| Kolkata Knight Riders | Eden Gardens                         | 2015-05-09 |
| Chennai Super Kings   | Wankhede Stadium                      | 2018-04-07 |
| Sunrisers Hyderabad   | Rajiv Gandhi International Stadium    | 2018-04-12 |
| Lucknow Super Giants  | M Chinnaswamy Stadium, Bengaluru      | 2023-04-10 |

### 5. **Highest Successful Chases and Team Totals**
- Showcased the highest successful run chases and team totals.

  **Highest Successful Chases**

| Score | Winner                | Venue                          | Date       |
|-------|-----------------------|--------------------------------|------------|
| 262   | Punjab Kings          | Eden Gardens, Kolkata          | 2024-04-26 |
| 224   | Rajasthan Royals      | Sharjah Cricket Stadium        | 2020-09-27 |
| 224   | Rajasthan Royals      | Eden Gardens, Kolkata          | 2024-04-16 |
| 219   | Mumbai Indians        | Arun Jaitley Stadium, Delhi    | 2021-05-01 |
| 215   | Sunrisers Hyderabad   | Sawai Mansingh Stadium, Jaipur | 2023-05-07 |

**Highest Team Totals**

| Winner                | Score | Venue                                   | Date       |
|-----------------------|-------|-----------------------------------------|------------|
| Sunrisers Hyderabad   | 288.0 | M Chinnaswamy Stadium, Bengaluru       | 2024-04-15 |
| Sunrisers Hyderabad   | 278.0 | Rajiv Gandhi International Stadium, Uppal, Hyderabad | 2024-03-27 |
| Kolkata Knight Riders | 273.0 | Dr. Y.S. Rajasekhara Reddy ACA-VDCA Cricket Stadium, Visakhapatnam | 2024-04-03 |
| Sunrisers Hyderabad   | 267.0 | Arun Jaitley Stadium, Delhi             | 2024-04-20 |
| Royal Challengers Bangalore | 264.0 | M Chinnaswamy Stadium                | 2013-04-23 |


### 6. **Analyze team performances by win percentage**
- Analyzed win percentages to evaluate overall team performance across seasons.

| Team                        | Win Percentage |
|-----------------------------|----------------|
| Gujarat Titans              | 62.22 %        |
| Chennai Super Kings         | 57.98 %        |
| Mumbai Indians              | 55.17 %        |
| Lucknow Super Giants        | 54.55 %        |
| Kolkata Knight Riders       | 52.19 %        |
| Rajasthan Royals            | 50.68 %        |
| Sunrisers Hyderabad         | 48.35 %        |
| Royal Challengers Bangalore | 48.24 %        |
| Punjab Kings                | 45.53 %        |
| Delhi Capitals              | 44.04 %        |

---

## 🏏 **Player Knockout Match Stats**

### 1. **Most Runs and Wickets in Knockout Matches**
- Listed players with the highest runs and wickets in knockout stages.

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Most%20Runs%20In%20KnockOut%20Matches.png" alt="Win Percentage in Knockout Matches" width="60%">

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Most%20Wickets%20In%20KnockOut%20Matches.png" alt="Win Percentage in Knockout Matches" width="60%">

---

## 🏆 **Individual Batting Records**

### 1. **Most Career Runs**
- Highlighted players with the highest career runs in IPL history.

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Most%20Career%20Runs.png" alt="Win Percentage in Knockout Matches" width="60%">

### 2. **Highest Score By Players**

| No | Batter             | Highest Score |
|----|--------------------|---------------|
| 0  | CH Gayle           | 175           |
| 1  | BB McCullum        | 158           |
| 2  | Q de Kock          | 140           |
| 3  | AB de Villiers     | 133           |
| 4  | KL Rahul           | 132           |
| 5  | Shubman Gill       | 129           |
| 6  | AB de Villiers     | 129           |
| 7  | CH Gayle           | 128           |
| 8  | RR Pant            | 128           |
| 9  | M Vijay            | 127           |

### 3. **Most Centurie Players**

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Highest%20Scores%20and%20Centuries.png" alt="Win Percentage in Knockout Matches" width="60%">

### 4. **Most Sixes In IPL**
- Identified players with the most sixes over their IPL careers.

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Most%20Career%20Sixes.png" alt="Win Percentage in Knockout Matches" width="60%">

---

## 🎯 **Individual Bowling Records**

### 1. **Total Wickets Taken**
- Summarized total wickets taken by each bowler to assess their impact.

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Total%20Wickets%20Taken.png" alt="Win Percentage in Knockout Matches" width="60%">

---

## 🏅 **Fielding Records**

### 1. **Top Fielders by Catches**
- Ranked the top fielders based on catches taken.

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Top%20Fielders%20by%20Catches.png" alt="Win Percentage in Knockout Matches" width="60%">

---

## 📍 **Match Outcomes**

### 1. **Average Inning Scores by Venue**
- Analyzed average scores for first and second innings across different venues.

| No | Venue                                      | 1st Inning Avg Score | 2nd Inning Avg Score |
|----|--------------------------------------------|----------------------|----------------------|
| 0  | Dubai International Cricket Stadium        | 163.76               | 149.09               |
| 1  | Eden Gardens                               | 160.18               | 147.06               |
| 2  | Feroz Shah Kotla                           | 161.63               | 145.38               |
| 3  | M Chinnaswamy Stadium                      | 168.06               | 143.28               |
| 4  | MA Chidambaram Stadium, Chepauk            | 166.02               | 151.85               |
| 5  | MA Chidambaram Stadium, Chepauk, Chennai   | 164.54               | 151.57               |
| 6  | Narendra Modi Stadium, Ahmedabad           | 175.75               | 163.83               |
| 7  | Punjab Cricket Association Stadium, Mohali | 163.29               | 150.63               |
| 8  | Rajiv Gandhi International Stadium, Uppal  | 156.14               | 146.98               |
| 9  | Sawai Mansingh Stadium                     | 157.68               | 145.81               |
| 10 | Sharjah Cricket Stadium                    | 159.04               | 147.50               |
| 11 | Sheikh Zayed Stadium                       | 158.86               | 145.62               |
| 12 | Wankhede Stadium                           | 166.03               | 154.38               |
| 13 | Wankhede Stadium, Mumbai                   | 177.11               | 169.27               |


### 2. **Analyze the margins of wins by runs and wickets.**

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Analyze%20the%20margins%20of%20wins%20by%20runs%20and%20wickets.%201.png" alt="Win Percentage in Knockout Matches" width="60%">

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Analyze%20the%20margins%20of%20wins%20by%20runs%20and%20wickets.%202.png" alt="Win Percentage in Knockout Matches" width="60%">

### 3. **Toss Impact on Match Results For Every Seasons**

<img src="https://github.com/Bhushan148/IPL-Stats-Analysis/blob/main/About%20Project%20Material/Toss%20Impact%20on%20Match%20Results%20For%20Every%20Seasons.png" alt="Win Percentage in Knockout Matches" width="60%">

---

## 🌤 **Impact of Venue and Weather Conditions**

- **Venue Analysis**: Explored how various venues affect team performance.
- **Weather Conditions**: Investigated the influence of weather on match outcomes and player performance.

---

## 💡 **Additional Insights**

- **Trend Analysis**: Identified significant trends in team and player performances over multiple seasons.
- **Performance Metrics**: Compared performance metrics across different teams and players.
- **Strategic Insights**: Provided actionable insights for teams and players based on historical data and trends.

---

## 📝 **Conclusion**

The IPL Dataset Analysis offers a detailed examination of IPL cricket, focusing on player and team performances, match results, and key metrics. It highlights trends, top performers, and strategic insights, providing valuable information for teams, players, and stakeholders. This project underscores the importance of player consistency, strategic team planning, and understanding match conditions.

---

## 🔗 **See All About Project Material**

- **Kaggle Dataset**: [Link to Dataset](https://www.kaggle.com/datasets/patrickb1912/ipl-complete-dataset-20082020)

---

## 🌟 **See More Projects**

- **Project Development and Author Information**
  - **Developed By**: Bhushan Gawali
  - **Role**: Data Analyst
  - **Contact Information**:
    - [LinkedIn Profile](https://www.linkedin.com/in/bhushan-gawali-97b645233?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
    - [GitHub Profile](https://github.com/Bhushan148)
    - [Email](https://accounts.google.com/SignOutOptions?hl=en&continue=https://myaccount.google.com/%3Fpli%3D1&ec=GBRAwAE)
    - [WhatsApp](https://wa.me/qr/45BQWP6TQQ24M1)
    - [Instagram](https://www.instagram.com/bhushangawali_148?igsh=ZXVkYXo4NnU3c2ps)
  - **Date**: 25/06/2024

---

## 📈 **Project Development**

Developed by Bhushan Gawali, leveraging expertise in data analysis and visualization. This project involved:

- **Data Collection**: Gathered IPL match and delivery data.
- **Data Cleaning**: Addressed missing values and corrected data types.
- **Exploratory Data Analysis (EDA)**: Analyzed match results, runs, and wickets.
- **Team & Player Stats**: Evaluated team performances, player records, and fielding stats.
- **Match Outcomes**: Studied average scores, win margins, and toss impacts.

---

**Dive into the IPL dataset and uncover the secrets behind the thrilling matches!**

