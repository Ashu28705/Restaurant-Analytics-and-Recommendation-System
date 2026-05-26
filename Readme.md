# 🍽️ Cognifyz Machine Learning Internship Project

## 📌 Overview

This repository contains the projects completed during my **Machine Learning Internship at Cognifyz Technologies**. The internship focused on applying Machine Learning, Data Analysis, and Recommendation System techniques on a restaurant dataset to extract meaningful insights and build intelligent solutions.

The project covers:

- Restaurant Rating Prediction
- Restaurant Recommendation System
- Location-Based Restaurant Analysis

---

## 🏢 Internship Details

| Field | Details |
|---------|---------|
| Organization | Cognifyz Technologies |
| Domain | Machine Learning |
| Intern | Ashutosh Kamboya |
| Duration | Internship Program |
| Dataset | Restaurant Dataset |

---

## 📂 Dataset Information

The dataset contains information about restaurants from multiple cities and countries.

### Dataset Statistics

- Total Records: **9551**
- Total Features: **21**
- Missing Values: **9 (Cuisines column)**
- Duplicate Records: **0**

### Features Include

- Restaurant Name
- City
- Locality
- Latitude
- Longitude
- Cuisines
- Average Cost for Two
- Price Range
- Aggregate Rating
- Votes
- Online Delivery
- Table Booking
- Currency

---

# 📊 Exploratory Data Analysis (EDA)

Several exploratory analyses were performed before building machine learning models.

### Key Findings

✅ Majority of restaurant ratings fall between **3.0 and 4.0**

✅ Restaurants offering **online delivery** generally have higher ratings

✅ Restaurants providing **table booking facilities** tend to receive better customer ratings

✅ **North Indian cuisine** is the most common cuisine in the dataset

✅ **Price Range** and **Votes** show the strongest correlation with restaurant ratings

### Visualizations

- Rating Distribution
- Correlation Heatmap
- Top Cities by Restaurant Count
- Top Cities by Average Rating
- Top Cuisine Analysis
- Online Delivery Impact
- Table Booking Impact

---

# 🤖 Task 1: Restaurant Rating Prediction

## Objective

Build a Machine Learning model to predict restaurant ratings based on restaurant characteristics.

## Data Preprocessing

- Handled missing values
- One-Hot Encoded categorical features
- Converted binary variables into numerical format
- Removed irrelevant columns
- Split data into training and testing sets

## Models Used

### Linear Regression

Performance:

| Metric | Value |
|----------|----------|
| MAE | 0.9846 |
| RMSE | 1.3345 |
| R² Score | 0.2175 |

### Random Forest Regressor

Performance:

| Metric | Value |
|----------|----------|
| MAE | 0.1918 |
| RMSE | 0.2979 |
| R² Score | 0.9610 |

## Feature Importance

Most influential features:

1. Votes
2. Longitude
3. Latitude
4. Average Cost for Two
5. Country Code
6. Online Delivery
7. Price Range
8. Table Booking
9. Cuisine Type
10. Locality

## Conclusion

Random Forest significantly outperformed Linear Regression and successfully captured complex non-linear relationships between restaurant features and ratings.

---

# 🍽️ Task 2: Restaurant Recommendation System

## Objective

Develop a content-based recommendation system that suggests restaurants similar to a user's preferred restaurant.

## Methodology

- Selected restaurant attributes:
  - Cuisine
  - City
  - Price Range
- Combined attributes into a unified feature profile
- Applied CountVectorizer
- Calculated similarity using Cosine Similarity
- Generated recommendations based on similarity scores

## Technologies Used

- CountVectorizer
- Cosine Similarity
- Pandas
- Scikit-Learn

## Sample Recommendation

Input Restaurant:

```python
recommend_restaurant("Barbeque Nation")
```

Recommended Restaurants:

- Carnival By Tresind
- Punjab Grill
- Tresind - Nassima Royal Hotel
- Prankster
- Gazebo Restaurant

## Conclusion

The recommendation engine successfully generated relevant restaurant suggestions based on cuisine, location, and pricing characteristics.

---

# 📍 Task 4: Location-Based Analysis

## Objective

Perform geographical analysis using restaurant location data.

## Analysis Performed

### Restaurant Distribution

- Visualized restaurant locations using latitude and longitude coordinates
- Identified geographical restaurant clusters

### City Analysis

Analyzed:

- Restaurant count by city
- Average ratings by city
- Average cost by city

### Locality Analysis

Identified the top restaurant-dense localities including:

- Connaught Place
- Rajouri Garden
- Shahdara
- Defence Colony
- Malviya Nagar

### Price Range Analysis

Observed that:

- Budget and mid-range restaurants dominate the dataset
- Premium restaurants form a smaller portion

## Key Insights

- New Delhi contains the highest concentration of restaurants
- Several international cities achieved the highest average ratings
- Restaurants cluster around metropolitan and commercial regions
- Location influences restaurant density but not necessarily customer ratings

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# 📁 Project Structure

```text
Cognifyz-Machine-Learning-Internship/
│
├── Dataset.csv
│
├── Task1_Restaurant_Rating_Prediction.ipynb
├── Task2_Restaurant_Recommendation_System.ipynb
├── Task4_Location_Based_Analysis.ipynb
│
├── images/
│   ├── rating_distribution.png
│   ├── correlation_heatmap.png
│   ├── top_cities.png
│   ├── recommendation_output.png
│   ├── locality_analysis.png
│   └── geographical_distribution.png
│
├── models/
│   └── restaurant_rating_model.pkl
│
└── README.md
```

---

# 📈 Results Summary

| Task | Outcome |
|--------|---------|
| Restaurant Rating Prediction | Random Forest achieved R² = 0.961 |
| Restaurant Recommendation System | Generated relevant content-based recommendations |
| Location-Based Analysis | Identified city-wise and locality-wise restaurant patterns |

---

# 🎯 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Regression Modeling
- Recommendation Systems
- Geographical Data Analysis
- Data Visualization
- Model Evaluation

---

# 📜 Internship Completion

Successfully completed the following Machine Learning Internship tasks at **Cognifyz Technologies**:

✅ Restaurant Rating Prediction

✅ Restaurant Recommendation System

✅ Location-Based Analysis

---

# 👨‍💻 Author

**Ashutosh Kamboya**

- GitHub: https://github.com/Ashu28705
- LinkedIn: Add Your LinkedIn Profile Here

---

⭐ If you found this project useful, consider giving it a star!