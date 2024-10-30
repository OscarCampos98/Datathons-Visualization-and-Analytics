# Airbnb Data Analysis - Datathon 1

## Project Overview

This project analyzes Airbnb property prices across three major cities: **Vancouver**, **London**, and **Bangkok**. Using datasets from June 2023, we explore the price variations across different neighborhoods, the proximity of expensive listings to city centers, and the relationship between average prices and ratings.

### Dataset
The dataset is sourced from the [Inside Airbnb](https://drive.google.com/drive/folders/10he8tIAXCZKb9MxdlYYtfKBbDHwqOful) project, which provides detailed listings of Airbnb properties from 2023. For this project, the following datasets were used:
- **Vancouver**
- **London**
- **Bangkok**

The data includes:
- Prices (in local currencies)
- Room types
- Location (latitude and longitude)
- Number of reviews and ratings

### Currency Conversion
To standardize prices across the cities, all prices were converted to **Canadian Dollars (CAD)** using the following exchange rates:
- **Bangkok**: ฿26.7418 Thai Baht = $1 CAD (as of June 26, 2023)
- **London**: £0.5958 GBP = $1 CAD (as of June 8, 2023)

## Data Cleaning Process
The data was cleaned using **Google Colab** with **Python libraries** such as **Pandas** and **re** for preprocessing. You can view the full data cleaning process in the Google Colab file linked below.

[Google Colab: Data Cleaning](https://github.com/OscarCampos98/Datathons-Visualization-and-Analytics/blob/main/DataCleaning_Datathon2.ipynb)

## Analysis Question
**How do Airbnb property prices vary across different cities, and where are the most expensive properties located within those cities?**

---

## Visualizations

![Average Airbnb Prices by City](https://raw.githubusercontent.com/OscarCampos98/Datathons-Visualization-and-Analytics/main/Visualization1_AVGprice.png)

### 1. Average Airbnb Prices Across Major Cities Top 5 Most Expensive Neighborhoods in Each City (Star rating incorporated)
This visualization shows the average prices (in CAD) across the three cities: Vancouver, London, and Bangkok. The most expensive city is London, followed by Vancouver, while Bangkok has significantly lower average prices.

London:
The most expensive neighborhood in London is Kensington and Chelsea, with an average price of $489 CAD. However, it doesn't have the highest star rating, which is given to the City of London (average rating of 4.0/5).
Other high-cost neighborhoods like Westminster also appear on the list but with lower ratings.

Vancouver:
Marpole is the most expensive neighborhood with an average price of $472 CAD, and a high rating of 4.00/5.
Interestingly, Shaughnessy has the highest rating at 4.25/5, but it’s only the third most expensive neighborhood.

Bangkok:
Taling Chan has an unusually high average price of $3047 CAD, which is due to one extremely high-priced listing skewing the average. This neighborhood doesn't have the highest rating either.
Khan Na Yao, one of the least expensive neighborhoods, surprisingly has one of the highest ratings, indicating that lower-cost areas may offer a better guest experience.


### 2. Price Distribution Across Neighborhoods (Visualization 2 - Maps):

#### Vancouver Map:
![Vancouver Map](https://raw.githubusercontent.com/OscarCampos98/Datathons-Visualization-and-Analytics/main/Visualization2_VanMap.png)

#### London Map:
![London Map](https://raw.githubusercontent.com/OscarCampos98/Datathons-Visualization-and-Analytics/main/Visualization2_LonMap.png)

#### Bangkok Map:
![Bangkok Map](https://raw.githubusercontent.com/OscarCampos98/Datathons-Visualization-and-Analytics/main/Visualization2_BangMap.png)

---

## Insights

- **Vancouver**: The map demonstrates that the most expensive neighborhoods, like Marpole, are not located close to downtown Vancouver. Marpole is approximately 7.71 km (4.79 miles) from downtown, while the least expensive neighborhood, Renfrew-Collingwood, is much closer at 5.53 km (3.43 miles).

Insight: The most expensive properties in Vancouver are not concentrated in the city center..

- **London**: The most expensive neighborhood, Kensington and Chelsea accordind to visualization 1, is 5.28 km (3.28 miles) from the center of London. Other expensive areas, such as Wandsworth, Bexley, and Havring have single listings which are higher in price $1000+ but the listings are of a single Airbnb, these listings are also further away from the center of london.
  
In contrast, the least expensive neighborhoods, like Croydon, are further away from central London, about 22.75 km (14.14 miles).

- **Bangkok**: The most expensive neighborhood, **Taling Chan**, is located 10 km (6 miles) from the center, while the least expensive neighborhood, **Nong Khaem**, is 18 km (11 miles) away.

---

## Conclusion

This analysis reveals that Airbnb prices vary significantly across cities and neighborhoods, with the highest prices typically located outside city centers in Vancouver and London, while the relationship between price and proximity to the city center is less clear in Bangkok. Interestingly, price doesn’t necessarily correlate with the highest ratings, as some of the most expensive neighborhoods do not offer the best guest experiences. Additionally, outlier listings (such as the one in Taling Chan, Bangkok) can significantly skew average prices, highlighting the importance of careful interpretation of data when making decisions based on averages.

---
