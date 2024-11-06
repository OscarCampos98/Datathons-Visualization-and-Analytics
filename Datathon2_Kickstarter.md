# Kickstarter Data Analysis - Datathon 2

## Project Overview

This project examines Kickstarter project funding trends from 2009 to 2024. Through this analysis, we explore the average distance to funding goals, funds raised beyond those goals (surplus), and overall project success rates over time. Insights into project launch frequency and achievement rates highlight how funding dynamics have evolved since Kickstarter's inception.

### Dataset
The dataset is sourced from the [Kickstarter dataset from Web Robots.](https://webrobots.io/kickstarter-datasets/). This project examines Kickstarter project funding trends from 2009 to 2024. Through this analysis, we explore the average distance to funding goals, funds raised beyond those goals (surplus), and overall project success rates over time. Insights into project launch frequency and achievement rates highlight how funding dynamics have evolved since Kickstarter's inception.
You can find the 6 datasets used in the following [Google drive](https://drive.google.com/drive/folders/10he8tIAXCZKb9MxdlYYtfKBbDHwqOful)  
- **`created_at`** and **`launched_at`** dates
- **`distance_to_goal`**: Remaining funds needed to meet the goal (0 if already met)
- **`surplus_funding`**: Amount raised beyond the goal (0 if not exceeded)

## Data Cleaning Process
Data was cleaned in Google Colab using Python libraries such as Pandas and `re`. The cleaning steps included handling missing values, parsing JSON fields to extract key information (such as category and location), and calculated fields like distance_to_goal and surplus_funding. You can view the complete data cleaning process in the Google Colab file linked below.
[Google Colab: Data Cleaning](https://github.com/OscarCampos98/Datathons-Visualization-and-Analytics/blob/main/DataCleaning_Datathon2.ipynb)

## Analysis Question
**How have Kickstarter funding trends changed over time in terms of distance to funding goals, surplus funds raised, and project success rates?**

---

## Visualizations

### 1. Funding Trends Over Time: Distance to Goal and Surplus Analysis

![Funding Trends Over Time: Distance to Goal and Surplus Analysis](https://github.com/OscarCampos98/Datathons-Visualization-and-Analytics/blob/main/Datathon2_Kickstarter_Vis1.png)

This visualization tracks the average distance to goal and surplus funding by month and year, illustrating changes in project funding outcomes over time.

- **Distance to Goal**: In Kickstarter’s early years, projects consistently met or exceeded their goals, with average distances close to zero. This trend shifted over time, with notable increases in unmet goals starting in November 2014, followed by August 2017 and peaking in May 2022.
- **Surplus Funding**: The surplus funding trend follows a similar pattern, with August 2012 marking the first significant surplus, followed by larger surpluses in August and November 2020 and October 2023.
 

### 2. Kickstarter Project Launch Trends and Goal Achievement Rates:

![Project Launch Trends and Goal Achievement Rates](https://github.com/OscarCampos98/Datathons-Visualization-and-Analytics/blob/main/Datathon2_Kickstarter_Vis2.png)

This visualization shows the number of projects launched each year and the percentage that achieved their funding goals.

- **Early Years (2009-2011)**: Kickstarter's early projects saw higher success rates, with a smaller number of projects and a higher goal achievement percentage.
- **2023**: The most successful year for project launches and goal achievements, marking both high participation and a notable success rate.
- **Increasing Projects, Decreasing Success**: Over time, as the number of projects increased, the success rate declined, indicating heightened competition and challenges in securing funding.
- 
---

## Insights

- **Funding Success**: Kickstarter’s early years saw a higher rate of goal achievement, likely due to less competition and more targeted projects.
- **Increased Surplus in Recent Years**: Recent data show larger surpluses for successful projects, indicating strong financial support for select campaigns.
- **Competitive Landscape**: As Kickstarter grew, so did the competition for funding. Many projects now face more significant challenges in reaching their funding goals despite an increase in pledges.

---

## Conclusion

This analysis highlights the evolving funding dynamics on Kickstarter. Early on, projects often reached their goals, while recent years show both high unmet funding needs and large surpluses for successful projects. This suggests that the platform’s growth has made it increasingly competitive, with projects needing to stand out more to achieve their funding goals. The findings underscore the importance of strategic project presentation and goal setting for success on Kickstarter.

---
