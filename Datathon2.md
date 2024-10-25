# Airbnb Data Analysis - Datathon 2

## Project Overview

This project analyzes Airbnb property prices across three major cities: **Vancouver**, **London**, and **Bangkok**. Using datasets from June 2023, we explore the price variations across different neighborhoods, the proximity of expensive listings to city centers, and the relationship between average prices and ratings.

### Dataset
The dataset is sourced from the [Inside Airbnb]([http://insideairbnb.com/get-the-data.html](https://drive.google.com/drive/folders/10he8tIAXCZKb9MxdlYYtfKBbDHwqOful)) project, which provides detailed listings of Airbnb properties from 2023. For this project, the following datasets were used:
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

[Google Colab: Data Cleaning]([#link-to-colab](https://github.com/OscarCampos98/Datathons-Visualization-and-Analytics/blob/main/DataCleaning_Datathon2.ipynb))

## Analysis Question
**How do Airbnb property prices vary across different cities, and where are the most expensive properties located within those cities?**

---

## Visualizations

### 1. Average Airbnb Prices Across Major Cities
This visualization shows the average prices (in CAD) across the three cities: Vancouver, London, and Bangkok. The most expensive city is London, followed by Vancouver, while Bangkok has significantly lower average prices.

![Average Airbnb Prices by City]([./Visualization1_AVGprice.png](https://github.com/OscarCampos98/Datathons-Visualization-and-Analytics/blob/main/Visualization1_AVGprice.png))

### 2. Top 5 Most Expensive and Least Expensive Neighborhoods
For each city, we analyzed the top 5 most and least expensive neighborhoods. The results show that the most expensive properties are often located outside the city center in Vancouver and London, while in Bangkok, the relationship is less clear.

#### Vancouver Map:
![Vancouver Map]([./Visualization2_VanMap.png](https://github.com/OscarCampos98/Datathons-Visualization-and-Analytics/blob/main/Visualization2_VanMap.png))

#### London Map:
![London Map]([./Visualization2_LonMap.png](https://github.com/OscarCampos98/Datathons-Visualization-and-Analytics/blob/main/Visualization2_LonMap.png))

#### Bangkok Map:
![Bangkok Map]([./Visualization2_BangMap.png](https://github.com/OscarCampos98/Datathons-Visualization-and-Analytics/blob/main/Visualization2_BangMap.png))

---

## Insights

- **Vancouver**: The most expensive neighborhood, **Marpole**, is about 7.71 km (4.79 miles) from downtown Vancouver, whereas the least expensive neighborhood, **Renfrew-Collingwood**, is 5.53 km (3.43 miles) away.
- **London**: The most expensive neighborhood, **Kensington and Chelsea**, is located about 5.28 km (3.28 miles) from the city center. The least expensive neighborhoods, such as **Croydon**, are farther from central London at around 22.75 km (14.14 miles).
- **Bangkok**: The most expensive neighborhood, **Taling Chan**, is located 10 km (6 miles) from the center, while the least expensive neighborhood, **Nong Khaem**, is 18 km (11 miles) away.

---

## Conclusion
Airbnb prices vary significantly across cities, with the highest prices often found outside city centers in Vancouver and London. Interestingly, price does not always correlate with the highest ratings, suggesting that more expensive properties do not necessarily offer a better guest experience.

For detailed analysis and insights, refer to the visualizations and the data cleaning process outlined in the Google Colab file.

---

## How to Run This Project
1. Clone the repository.
2. Open the **Google Colab** file to review the data cleaning process.
3. View the visualizations provided in this README.

