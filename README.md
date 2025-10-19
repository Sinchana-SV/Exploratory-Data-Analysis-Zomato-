# 🍔🍴 Zomato Bengaluru Restaurant Data Analysis

<img src=https://the420.in/wp-content/uploads/2025/04/Zomato-Bans-AI.webp>

## 📊 Project Overview

Bengaluru’s restaurant industry is booming with over **12,000+ restaurants** serving a wide variety of cuisines.  
However, with such intense competition, **new entrants struggle to stand out**.  

The goal of this project is to leverage **data analysis and visualization** to uncover patterns and factors that contribute to restaurant success.  
Using the Zomato Bengaluru dataset, this project explores customer preferences, location dynamics, and rating patterns to provide **actionable insights** for restaurateurs and food lovers alike.

---

## 🎯 Problem Statement

> **Objective:**  
> Harness the power of data to predict restaurant success factors and help new ventures thrive,  
> while assisting customers in discovering the best dining experiences in Bengaluru.

---

## 📂 Dataset

**Source:** [Zomato Bengaluru Dataset on Kaggle](https://www.kaggle.com/datasets/absin7/zomato-bangalore-dataset)

### 🧾 Column Description

| Column | Description |
|--------|-------------|
| `url` | Restaurant webpage on Zomato |
| `address` | Address of the restaurant |
| `name` | Name of the restaurant |
| `online_order` | Availability of online ordering |
| `book_table` | Table booking availability |
| `rate` | Overall rating out of 5 |
| `votes` | Total number of votes received |
| `phone` | Restaurant contact number |
| `location` | Area or neighborhood |
| `rest_type` | Type of restaurant (e.g., Casual Dining, Cafe) |
| `dish_liked` | Popular dishes liked by customers |
| `cuisines` | Cuisines offered |
| `approx_cost(for two people)` | Average cost for two |
| `reviews_list` | List of customer reviews and ratings |
| `menu_item` | Menu items available |
| `listed_in(type)` | Type of meal (e.g., Buffet, Delivery) |
| `listed_in(city)` | City area or region listed |

---

## 🔎 Analysis Summary

### 1️⃣ Data Cleaning and Preprocessing 🧹
- **Handling Missing Values** → Removed rows with missing critical data
- **Column Cleaning** → Handling / , and blank spaces from the values in the columns
- **Aggregating the values** → Converted the values to "Others" wherever the count was less than 1000 

### 2️⃣ Exploratory Data Analysis (EDA) with Key Insights 👾
- **Number of Restaurants by Location** - High concentration in popular areas – The top 5 locations (e.g., Koramangala, Indiranagar, etc.) have a significantly higher restaurant density, showing these are prime dining hubs with strong customer footfall and competition.
- **Various Types of Restaurant** - Casual Dining dominates – It is the most common restaurant type by a wide margin, with around 7,400 outlets, showing strong customer preference for sit-down dining experiences.
- **The Top rated restaurants from each Area** - Premium and specialty brands perform strongly – Many highest-rated restaurants are well-known for specific cuisines (e.g., barbeque, desserts, or coffee), indicating that specialization helps secure top ratings.
- **Best choice of the Restaurant for different Cuisine** - Dessert-focused restaurants dominate top ratings – Belgian Waffle Factory and Milano Ice Cream lead their categories with ratings close to 5, showing strong customer preference for sweet-focused cuisines.
- **Online and book table based on rest_type** - Casual Dining dominates – It has the highest number of restaurants without online ordering or table booking, surpassing 7,000, indicating this type is the most common in this category.
- **Dish liked with type and cost_for_two** - Casual Dining leads significantly – It’s the top restaurant type without online ordering or table booking, exceeding 7,000 listings.
- **Cost for Two by Type of Restaurants** - Casual Dining dominates – It’s the most common restaurant type, far surpassing all others in count while niche categories are minimal – Types like Buffet, Pub, and Microbrewery have very few outlets, indicating a highly specialized market.
- **How the Cost varies based on different Location** - High-End Areas: Locations like Brigade Road and Church Street have the highest average cost for two, exceeding ₹1400.
- **Do restaurants with table booking have better ratings?** - Offering table booking might improve customer satisfaction and ratings.
Consistency in ratings suggests that booking restaurants may deliver more predictable experiences.
- **Which restaurant has the best rating per rupee spent** - Low cost with high ratings is a competitive edge in the food industry.

---

## 💡 Future Enhancements

🔰Build a predictive model to forecast restaurant success

⭐Perform sentiment analysis on customer reviews

📊Develop a dashboard in Power BI or Tableau for dynamic insights

---

## 🛠 Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---
