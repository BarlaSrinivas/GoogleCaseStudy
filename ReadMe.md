# 🚲 Cyclistic Bike-Share Case Study

Welcome to the **Cyclistic Bike-Share Case Study** repository! This project was part of the **Google Data Analytics Capstone**. It demonstrates how data analytics can help solve business challenges, specifically understanding the usage patterns of Cyclistic's bike-share system and identifying strategies to convert casual riders into annual members.


## 📜 Blog Post

Read the full write-up of the case study on Medium:  
[**Unlocking the Power of Data: A Cyclistic Bike-Share Case Study**](https://medium.com/@srinivasbarla2000/unlocking-the-power-of-data-a-cyclistic-bike-share-case-study-ddb9e3b9b061)


## 🌟 Overview

Cyclistic is a bike-share company in Chicago that operates over 5,800 bicycles and 600 docking stations. The goal of this case study is to analyze user behavior and design strategies to increase the number of annual memberships.

Key business question:  
**How do annual members and casual riders use Cyclistic bikes differently?**

Using Python for data cleaning and feature engineering, and Tableau for data visualization, this project provides actionable insights into customer behavior.

## Data Source

The data for this project was sourced from Cyclistic's historical trip data. While the exact Kaggle dataset is not specified, similar datasets can be found on Kaggle, such as the [Divvy Bicycle Sharing Dataset](https://www.kaggle.com/datasets/yingwurenjian/chicago-divvy-bicycle-sharing-data).

## Tools Used

- **Python**: Data cleaning, preprocessing, and analysis
- **Pandas & NumPy**: Data manipulation and numerical computations
- **Matplotlib**: Basic data visualization for EDA
- **Jupyter Notebooks**: Documentation of data cleaning and analysis processes
- **Tableau**: Creating interactive dashboards and advanced visualizations
- **Git**: Version control


## 📂 Repository Structure

```bash
├── data/                           # Data files (raw, interim, and cleaned)
│   ├── raw/                        # Raw datasets (not included)
│   ├── interim/                    # Preprocessed datasets
│   └── final/                      # Final datasets for visualization
├── notebooks/                      # Jupyter Notebooks
│   ├── data_cleaning.ipynb         # Data cleaning and preprocessing
│   └── analysis.ipynb              # Exploratory data analysis
├── visualizations/                 # Tableau dashboard and exported visuals
├── README.md                       # Documentation
└── LICENSE                         # License for the repository
```


## 🌟 Tableau Dashboard

Explore the interactive Tableau dashboard to view:  
- Insights into ridership trends by time, day, and season.  
- Breakdown of ride durations, distances, and speeds.  
- Popular stations for starting and ending rides.

[**Click here to view the Tableau Dashboard**](https://public.tableau.com/app/profile/srinivas.barla/viz/CYCLISTIC_17336421351400/Dashboard4)

![Cyclistic Summary](Cyclistic-Summary.png "Cyclistic Summary")
[**Click here to view the Tableau Dashboard**](https://public.tableau.com/app/profile/srinivas.barla/viz/CYCLISTIC_17336421351400/Dashboard4)


## Data Pipeline

### 1. Data Acquisition
- Downloaded the Cyclistic trip data (likely in CSV format) from the provided source.
- Stored the raw data files in the `data/raw/` directory.

### 2. Data Cleaning and Preprocessing
Using Python and Pandas in Jupyter Notebooks (`notebooks/data_cleaning.ipynb`):
- Loaded the raw CSV files into pandas DataFrames.
- Handled missing values and removed duplicates.
- Converted data types (e.g., timestamps to datetime objects).
- Calculated ride durations and distances.
- Created new features such as day of week, month, and season.
- Filtered out outliers or erroneous data points.

### 3. Exploratory Data Analysis (EDA)
In `notebooks/analysis.ipynb`:
- Analyzed ride patterns by user type, day of week, month, and season.
- Investigated ride durations and distances.
- Explored popular start and end stations.
- Generated summary statistics and visualizations using matplotlib.

### 4. Feature Engineering
Created additional features to enhance analysis:
- Calculated average speed for each ride.
- Categorized rides based on duration (short, medium, long).
- Identified peak hours and rush hours.

### 5. Data Visualization with Tableau
- Imported the cleaned and feature-engineered dataset into Tableau.
- Created interactive dashboards showcasing:
  - Ridership trends by time, day, and season.
  - Ride duration and distance comparisons between member types.
  - Popular start and end stations.
  - User behavior patterns.

### 6. Insight Generation
Analyzed the visualizations to extract key findings and actionable insights.

## Key Insights

1. **Usage Patterns:**
   - Members tend to use bikes more on weekdays, suggesting commuting purposes.
   - Casual riders prefer weekend rides, indicating leisure use.
   - Afternoon rides are most popular across both user types.

2. **Seasonal Trends:**
   - Summer and fall see peak usage for both member types.
   - Winter shows a significant decline in ridership, especially among casual users.

3. **Ride Characteristics:**
   - Members generally take shorter rides compared to casual riders.
   - Casual riders are more likely to use bikes for longer, leisurely trips.

4. **Popular Stations:**
   - Identified high-traffic stations for targeted marketing efforts.
   - Some stations are more popular among casual riders, presenting conversion opportunities.


## ⚖️ License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

