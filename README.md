# Swiggy Restuarant Analysis - Power BI Dashboard

## Overview
This project provides a detailed analysis of restaurant data from Swiggy using Microsoft Power BI. The dashboard visualizes restaurant performance, delivery metrics, cuisine preferences, and regional distributions, offering insights to optimize operations and customer satisfaction.

## Dataset
File Name:   Swiggy_data.xlsx  
Description: The dataset contains information about restaurants, pricing, delivery times, ratings, and food types.

Note: All data cleaning and preprocessing were performed directly in Power BI during the dashboard creation process.

### Key Columns in the Dataset:
- ID - Unique identifier for each restaurant.
- Area - Geographic area where the restaurant is located.
- City - City name.
- Restaurant - Name of the restaurant.
- Price - Average price of a meal.
- Avg Rating - Average customer rating.
- Total Rating - Total number of ratings received.
- Food Type - Type of cuisine served.
- Address - Restaurant address.
- Delivery Time - Estimated delivery time in minutes.

## Dashboard Highlights
The Power BI report (Swiggy_Restuarant_Analysis.pbix) includes:
1. Overview Metrics:
   - Total Restaurants: 8.68K
   - Average Delivery Time: 53.97 minutes
   - Total Customer Ratings: 31.73K
2. Restaurant Distribution by Price Range:
   - Visualizes restaurant counts categorized by low, medium, and high price ranges.
3. Popular Cuisine Types:
   - Displays the most popular cuisines (e.g., Indian, Chinese, Fast Food).
4. Restaurant Count Across Top Cities:
   - Provides a heatmap of restaurants across major cities such as Mumbai, Bangalore, and Hyderabad.
5. Delivery Time Analysis:
   - Average delivery times analyzed across areas.
6. Top-Rated Restaurants:
   - Highlights restaurants with the highest average ratings.

## Tools Used
- Power BI - Data cleaning, preprocessing, visualization, and dashboard creation.

## Key Insights
- Most restaurants fall in the medium price range category.
- Indian and Chinese cuisines dominate restaurant offerings.
- Major cities like Mumbai, Bangalore, and Hyderabad have the highest restaurant counts.
- Delivery times vary by area, with opportunities for optimization in slower regions.

## Repository Structure

|-- Swiggy-Restaurant-Report
    |-- Swiggy_data.xlsx
    |-- Swiggy_Restaurant_Analysis.pbix
    |-- README.md (This file)


## Future Improvements
- Integrate customer feedback sentiment analysis.
- Add predictive modeling for delivery time optimization.
- Include revenue estimation metrics for deeper business insights.
