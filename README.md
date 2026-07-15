# 🍽️ Restaurant Rating Prediction & Business Analytics

> An end-to-end Data Science and Machine Learning project that analyzes restaurant data, uncovers business insights, performs feature engineering, and predicts restaurant ratings using multiple regression models.

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-F7931E?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0)
![Folium](https://img.shields.io/badge/Folium-Geospatial-green)

---

# 📌 Project Overview

Restaurant businesses generate large amounts of operational and customer feedback data. Understanding customer behavior, restaurant services, pricing, and cuisine popularity can help restaurants improve customer satisfaction and optimize business strategies.

This project performs a complete **Data Science workflow**, including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Geospatial Analysis
- Feature Engineering
- Customer Preference Analysis
- Machine Learning
- Business Insights
- Advanced Data Visualization

Finally, three regression models were trained to predict restaurant aggregate ratings.

---

# 🎯 Objectives

- Clean and preprocess restaurant data.
- Explore customer behavior through visual analytics.
- Analyze restaurant distribution across countries and cities.
- Perform feature engineering for machine learning.
- Train multiple regression models.
- Compare model performance.
- Generate actionable business insights.

---

# 📂 Dataset Information

**Dataset Size:** 9,551 Restaurants

### Key Features

- Restaurant Name
- Country
- City
- Locality
- Cuisines
- Average Cost for Two
- Price Range
- Aggregate Rating
- Rating Color
- Rating Text
- Votes
- Has Table Booking
- Has Online Delivery
- Latitude
- Longitude

Target Variable:

**Aggregate Rating**

---

# 🛠️ Technologies Used

| Category | Tools |
|----------|-------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Geospatial Analysis | Folium |
| Development | Jupyter Notebook, Google Colab |

---

# 📁 Project Structure

```text
Restaurant-Rating-Prediction-and-Analytics/
│
├── Dataset/
│   ├── Dataset.csv
│   ├── Cleaned_Dataset.csv
│   └── Feature_Engineered_Dataset.csv
│
├── Notebooks/
│   ├── Level_1/
│   ├── Level_2/
│   └── Level_3/
│
├── Images/
│
├── Report/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 🔄 Project Workflow

```text
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Geospatial Analysis
    │
    ▼
Feature Engineering
    │
    ▼
Machine Learning
    │
    ▼
Model Evaluation
    │
    ▼
Business Insights
```

---

# 📊 Exploratory Data Analysis

Performed:

- Missing Value Analysis
- Descriptive Statistics
- Country-wise Restaurant Distribution
- City-wise Restaurant Distribution
- Cuisine Analysis
- Price Range Analysis
- Table Booking Analysis
- Online Delivery Analysis

---

# 🌍 Geospatial Analysis

Interactive restaurant visualization was created using **Folium**.

### Features

- Interactive Map
- Marker Clustering
- Restaurant Details Popup
- Country Mapping

📷

![Geospatial Map](Images/Geospatial_Map.png)

---

# ⚙️ Feature Engineering

Created multiple engineered features including:

- Restaurant Name Length
- Address Length
- Cuisine Count
- Table Booking Encoding
- Online Delivery Encoding
- Delivering Now Encoding
- Rating Status
- High Rated Restaurant
- Cost Per Person
- Log Votes
- Price Category
- Cost Category

---

# 🤖 Machine Learning Models

The following regression algorithms were trained:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

# 📈 Model Performance

| Model | MAE | RMSE | R² Score |
|---------|---------|---------|---------|
| Linear Regression | 0.200 | 0.279 | 0.966 |
| Decision Tree | 0.233 | 0.372 | 0.939 |
| Random Forest | **0.169** | **0.255** | **0.971** |

🏆 **Best Model:** Random Forest Regressor

---

# 📷 Model Comparison

![Model Comparison](Images/Model_Comparison.png)

---

# ⭐ Feature Importance

The Random Forest model identified the most influential features for predicting restaurant ratings.

![Feature Importance](Images/Feature_Importance.png)

---

# 📉 Actual vs Predicted Ratings

The Random Forest model demonstrated excellent predictive performance.

![Prediction](Images/Actual_vs_Predicted.png)

---

# 🍽️ Customer Preference Analysis

The project analyzed:

- Most Popular Cuisines
- Highest Rated Cuisines
- Most Voted Restaurants
- Customer Satisfaction
- Online Delivery Preferences
- Table Booking Preferences

![Customer Preference](Images/Customer_Preference.png)

---

# 📊 Data Visualization

The project includes:

- Histograms
- Scatter Plots
- Bubble Charts
- Correlation Heatmap
- Pair Plot
- Violin Plot
- Box Plot
- Count Plot

![Correlation Heatmap](Images/Correlation_Heatmap.png)

---

# 💡 Key Business Insights

- Budget restaurants dominate the dataset.
- Restaurants with online delivery generally receive higher ratings.
- Table booking is associated with better customer satisfaction.
- Customer votes positively correlate with restaurant popularity.
- Random Forest achieved outstanding prediction accuracy (R² = 0.971).
- Feature engineering significantly improved predictive performance.

---

# 🚀 Future Scope

- Hyperparameter Optimization
- Deep Learning Models
- Restaurant Recommendation System
- Real-Time API Integration
- Streamlit Dashboard
- Power BI Dashboard
- Cloud Deployment

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Restaurant-Rating-Prediction-and-Analytics.git
```

Move to project folder

```bash
cd Restaurant-Rating-Prediction-and-Analytics
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 📚 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
folium
jupyter
notebook
```

---

# 👩‍💻 Author

**Lavishka Bhardwaj**

B.Tech – Artificial Intelligence & Data Science

GitHub: https://github.com/lavishka22

LinkedIn: *(Add your LinkedIn profile URL here)*

---

# ⭐ Support

If you found this project helpful, consider giving it a ⭐ on GitHub!

---

# 📄 License

This project is licensed under the **MIT License**.
