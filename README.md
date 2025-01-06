# AirBnB-Listing-Analysis - Python
Analyze AirBnB listings in Paris to determine the impact of recent regulations

## Project Overview
This project focuses on analyzing Airbnb listings to understand key trends and insights about host activity, pricing, and neighborhood patterns in Paris. Using Python, the project cleans and processes data, visualizes trends, and draws insights to inform business decisions.

## Key Objectives
- Analyze the impact of regulations on Airbnb hosts and pricing.
- Identify neighborhood-specific trends in pricing and accommodations.
- Understand how host activity and pricing patterns have evolved over time.

## Tools and Libraries
- **Python**: Primary language for analysis.
- **Pandas**: For data manipulation and cleaning.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Jupyter Notebook**: For an interactive and reproducible workflow.

## Dataset
The dataset used in this project contains Airbnb listings data. It includes fields such as:
- **Host Since**: Date when the host joined Airbnb.
- **Neighborhood**: The area where the listing is located.
- **Price**: The price of the listing per night.
- **Accommodates**: The number of people the listing can accommodate.

## Analysis Steps
1. **Data Loading and Exploration**:
   - Loaded the dataset using Pandas.
   - Explored data structure, missing values, and column types.

2. **Data Cleaning**:
   - Converted date fields to datetime format.
   - Filtered data for listings in Paris.
   - Dropped rows with missing values.

3. **Trend Analysis**:
   - Analyzed new host registrations over time.
   - Examined average listing prices by neighborhood and year.

4. **Visualization**:
   - Used line plots to visualize trends in new hosts and pricing.
   - Compared new host activity and pricing trends over time using dual y-axes.

## Key Insights
- **2015 Regulations**: Led to a significant decrease in new hosts but resulted in higher average prices.
- **Neighborhood Trends**: Certain neighborhoods have consistently higher prices, indicating premium locations.
- **Seasonality**: Observed patterns in host activity and pricing over time.

## Visualizations
1. **New Hosts Over Time**:
   - Highlighted the decline in new host registrations due to regulations.
2. **Average Prices Over Time**:
   - Showed how pricing has increased as host activity declined.
3. **Neighborhood Analysis**:
   - Compared average prices and accommodations across Paris neighborhoods.

## Project Files
- **AirBnB_Analysis.ipynb**: Jupyter Notebook containing the full analysis.
- **listings.csv**: Dataset used for the project.
- **Visualizations**: Plots showcasing key trends and insights.
