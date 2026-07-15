# 🍽️ Restaurant Rating Prediction & Business Analytics

> An end-to-end **Data Science & Machine Learning** project that analyzes restaurant data, performs exploratory data analysis (EDA), geospatial analysis, feature engineering, customer preference analysis, and predicts restaurant aggregate ratings using multiple regression models.

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-4C72B0)
![Folium](https://img.shields.io/badge/Folium-Geospatial-success)

---

# 📋 Table of Contents

- [Overview](#-overview)
- [Project Objectives](#-project-objectives)
- [Features](#-features)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Project Workflow](#-project-workflow)
- [Project Structure](#-project-structure)
- [Dataset](#-dataset)
- [Machine Learning Models](#-machine-learning-models)
- [Model Performance](#-model-performance)
- [Business Insights](#-business-insights)
- [Future Scope](#-future-scope)
- [Author](#-author)
- [License](#-license)

---

# 🎯 Overview

Restaurant businesses generate large volumes of customer feedback and operational data every day. Understanding customer preferences, restaurant services, pricing strategies, cuisine popularity, and geographical distribution can help restaurant owners improve customer satisfaction and business performance.

This project demonstrates a complete **Data Science workflow** using Python, beginning with raw restaurant data and ending with highly accurate machine learning predictions.

The project includes:

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Geospatial Analysis
- Feature Engineering
- Customer Preference Analysis
- Machine Learning
- Business Insights
- Advanced Data Visualization

The final model achieved an excellent **R² Score of 0.971** using the Random Forest Regressor.

---

# 🎯 Project Objectives

The primary objectives of this project are:

- Clean and preprocess restaurant data.
- Explore restaurant trends using statistical analysis.
- Analyze restaurant distribution across countries and cities.
- Understand customer behavior and preferences.
- Perform feature engineering to improve prediction accuracy.
- Build multiple regression models for restaurant rating prediction.
- Compare machine learning models using evaluation metrics.
- Generate meaningful business insights for restaurant owners.

---

# ✨ Features

✔ Data Cleaning & Preprocessing

✔ Exploratory Data Analysis (EDA)

✔ Geospatial Analysis using Folium

✔ Customer Preference Analysis

✔ Table Booking Analysis

✔ Online Delivery Analysis

✔ Price Range Analysis

✔ Feature Engineering

✔ Machine Learning Model Comparison

✔ Business Insights

✔ Interactive Visualizations

✔ Professional Documentation

---

# 🛠 Technologies Used

| Category | Tools |
|----------|-------|
| Programming Language | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Geospatial Analysis | Folium |
| Development Environment | Google Colab, Jupyter Notebook |
| Version Control | Git, GitHub |

---

# 🚀 Installation

## Prerequisites

- Python 3.9+
- Git
- Jupyter Notebook / Google Colab

---

## Clone Repository

```bash
git clone https://github.com/lavishka22/Restaurant-Rating-Prediction-and-Analytics.git
```

---

## Navigate to Project Folder

```bash
cd Restaurant-Rating-Prediction-and-Analytics
```

---

## Create Virtual Environment (Optional)

Windows

```bash
python -m venv venv

venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Launch Jupyter Notebook

```bash
jupyter notebook
```

or open the notebooks using **Google Colab**.

---

# 🔄 Project Workflow

```text
Restaurant Dataset
        │
        ▼
Data Cleaning & Preprocessing
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
│   │   ├── Level_1_Task_1_Data_Exploration.ipynb
│   │   ├── Level_1_Task_2_Descriptive_Analysis.ipynb
│   │   └── Level_1_Task_3_Geospatial_Analysis.ipynb
│   │
│   ├── Level_2/
│   │   ├── Level_2_Task_1_Table_Booking_Online_Delivery.ipynb
│   │   ├── Level_2_Task_2_Price_Range_Analysis.ipynb
│   │   └── Level_2_Task_3_Feature_Engineering.ipynb
│   │
│   └── Level_3/
│       ├── Level_3_Task_1_Predictive_Modeling.ipynb
│       ├── Level_3_Task_2_Customer_Preference_Analysis.ipynb
│       └── Level_3_Task_3_Data_Visualization.ipynb
│
├── Images/
│   ├── Correlation_Heatmap.png
│   ├── Feature_Importance.png
│   ├── Model_Comparison.png
│   ├── Actual_vs_Predicted.png
│   ├── Geospatial_Map.png
│   ├── Customer_Preference.png
│   ├── Rating_Distribution.png
│   └── Top_Cuisines.png
│
├── Report/
│   └── Restaurant_Analytics_Report.docx
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```
# 📊 Dataset

## Dataset Overview

This project is based on the **Zomato Restaurant Dataset**, which contains restaurant information from multiple countries and cities.

The dataset was analyzed, cleaned, transformed, and enhanced through feature engineering before building machine learning models.

---

## Dataset Statistics

| Attribute | Value |
|------------|--------|
| Total Restaurants | **9,551** |
| Countries | **15** |
| Cities | **141** |
| Original Features | **21** |
| Engineered Features | **12** |
| Target Variable | **Aggregate Rating** |

---

## Important Features

The dataset contains several important restaurant attributes including:

- Restaurant Name
- Country
- City
- Locality
- Latitude
- Longitude
- Cuisines
- Average Cost for Two
- Currency
- Price Range
- Aggregate Rating
- Rating Color
- Rating Text
- Votes
- Has Table Booking
- Has Online Delivery
- Is Delivering Now
- Switch to Order Menu

---

## Data Preprocessing

The following preprocessing steps were performed:

✔ Missing Value Handling

✔ Duplicate Record Checking

✔ Country Code Mapping

✔ Data Type Validation

✔ Feature Creation

✔ Encoding of Categorical Variables

✔ Cost Transformation

✔ Log Transformation of Votes

✔ Price Category Creation

✔ Feature Scaling Preparation

---

# ⚙️ Feature Engineering

To improve prediction accuracy, several new features were created.

### Engineered Features

| Feature | Description |
|----------|-------------|
| Restaurant Name Length | Number of characters in restaurant name |
| Address Length | Number of characters in address |
| Cuisine Count | Number of cuisines offered |
| Table Booking | Encoded binary feature |
| Online Delivery | Encoded binary feature |
| Delivering Now | Encoded binary feature |
| Rating Status | Rated / Not Rated |
| High Rated Restaurant | Binary classification feature |
| Cost Per Person | Average Cost for Two ÷ 2 |
| Log Votes | Log-transformed customer votes |
| Price Category | Budget / Affordable / Premium / Luxury |
| Cost Category | Low / Medium / High / Very High |

---

# 🤖 Machine Learning Models

Three supervised regression algorithms were trained and compared.

---

## 1️⃣ Linear Regression

Linear Regression was used as the baseline model.

It assumes a linear relationship between the input features and restaurant ratings.

### Performance

- MAE = **0.200**
- RMSE = **0.279**
- **R² = 0.966**

---

## 2️⃣ Decision Tree Regressor

Decision Tree Regressor captures non-linear relationships by recursively splitting the dataset into decision nodes.

### Performance

- MAE = **0.233**
- RMSE = **0.372**
- **R² = 0.939**

---

## 3️⃣ Random Forest Regressor ⭐

Random Forest combines multiple Decision Trees and averages their predictions.

It achieved the highest predictive accuracy among all models.

### Performance

- MAE = **0.169**
- RMSE = **0.255**
- **R² = 0.971**

🏆 **Best Performing Model**

---

# 📈 Model Performance Comparison

| Model | MAE ↓ | RMSE ↓ | R² Score ↑ |
|---------|---------|---------|---------|
| Linear Regression | 0.200 | 0.279 | 0.966 |
| Decision Tree Regressor | 0.233 | 0.372 | 0.939 |
| Random Forest Regressor | **0.169** | **0.255** | **0.971** |

---

## 📊 Performance Summary

- Lowest MAE ✅ Random Forest
- Lowest RMSE ✅ Random Forest
- Highest R² Score ✅ Random Forest

The Random Forest model explained approximately **97.1% of the variance** in restaurant ratings, making it the most reliable predictive model for this project.

---

# 🏆 Best Model

After comparing all regression algorithms, **Random Forest Regressor** was selected as the final model because it achieved:

- Highest Prediction Accuracy
- Lowest Prediction Error
- Best Generalization Performance
- Excellent R² Score of **0.971**

The combination of feature engineering and ensemble learning significantly improved prediction quality compared to the baseline models.
---

# 📌 Key Business Insights

The project generated several actionable business insights.

### Restaurant Market

- Budget restaurants dominate the dataset.
- India contributes the highest number of restaurants.
- Restaurant density is concentrated in major cities.

### Customer Behavior

- Restaurants with online delivery generally receive higher ratings.
- Table booking is associated with improved customer satisfaction.
- Customer votes positively correlate with restaurant popularity.

### Machine Learning

- Random Forest achieved the highest prediction accuracy.
- Feature engineering significantly improved model performance.
- Customer engagement features contributed strongly to prediction quality.

---

# 📈 Project Highlights

✅ 9,551 Restaurant Records

✅ 15 Countries

✅ 141 Cities

✅ 12+ Engineered Features

✅ Interactive Geospatial Analysis

✅ Customer Preference Analytics

✅ Multiple Regression Models

✅ Random Forest R² Score = **0.971**

✅ End-to-End Data Science Workflow

---

# 💼 Applications

The developed solution can be applied for:

- Restaurant Rating Prediction
- Restaurant Recommendation Systems
- Business Intelligence
- Customer Behavior Analysis
- Restaurant Expansion Planning
- Pricing Strategy Optimization
- Location-Based Analytics
- Food Delivery Analytics

---

# 🎯 Future Improvements

Future enhancements for this project include:

- Deep Learning Models
- XGBoost & LightGBM
- Hyperparameter Optimization
- Streamlit Dashboard
- Power BI Dashboard
- Real-Time Restaurant API Integration
- Restaurant Recommendation System
- Cloud Deployment (AWS / Azure)
---

# ⚙️ Requirements

The project requires the following Python libraries:

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
folium
jupyter
notebook
```

You can install all dependencies using:

```bash
pip install -r requirements.txt
```

---

# ▶️ How to Run the Project

## Step 1: Clone the Repository

```bash
git clone https://github.com/lavishka22/Restaurant-Rating-Prediction-and-Analytics.git
```

---

## Step 2: Navigate to the Project Folder

```bash
cd Restaurant-Rating-Prediction-and-Analytics
```

---

## Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

or open the notebooks using **Google Colab**.

---

## Step 5: Run the Notebooks in Order

### 📂 Level 1

- Data Exploration & Preprocessing
- Descriptive Analysis
- Geospatial Analysis

### 📂 Level 2

- Table Booking & Online Delivery Analysis
- Price Range Analysis
- Feature Engineering

### 📂 Level 3

- Predictive Modeling
- Customer Preference Analysis
- Advanced Data Visualization

---

# 📈 Project Outcomes

The project successfully achieved the following:

- Cleaned and analyzed a real-world restaurant dataset containing **9,551 records**.
- Performed comprehensive exploratory data analysis (EDA).
- Created **12+ engineered features** to improve model performance.
- Built and compared three regression models.
- Achieved an excellent **R² Score of 0.971** using the Random Forest Regressor.
- Generated actionable business insights related to customer preferences, restaurant services, pricing, and cuisine trends.
- Developed interactive geospatial visualizations using Folium.
- Created professional data visualizations to support business decision-making.

---

# 🏆 Key Achievements

✔ End-to-End Data Science Project

✔ Exploratory Data Analysis

✔ Geospatial Analytics

✔ Feature Engineering

✔ Machine Learning

✔ Business Analytics

✔ Customer Preference Analysis

✔ Interactive Visualizations

✔ Random Forest R² = **0.971**

---

# 📚 Learning Outcomes

Through this project, the following concepts were applied:

- Data Cleaning
- Missing Value Handling
- Feature Engineering
- Data Visualization
- Statistical Analysis
- Regression Modeling
- Model Evaluation
- Business Intelligence
- Customer Analytics
- Geospatial Analysis

---

# 🤝 Contributing

Contributions are welcome!

If you would like to improve this project:

1. Fork the repository.
2. Create a new feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push to GitHub.

```bash
git push origin feature-name
```

5. Create a Pull Request.

---

# ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

Your support helps motivate further improvements and future open-source projects.

---

# 👩‍💻 Author

## Lavishka Bhardwaj

**B.Tech – Artificial Intelligence & Data Science**

### Connect with me

📧 Email: lavishkabhardwaj376@gmail.com

🐙 GitHub: https://github.com/lavishka22

---

# 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project in accordance with the terms of the MIT License.

---

# 🙏 Acknowledgements

I would like to sincerely thank:

- **Cognifyz Technologies** for providing this internship opportunity.
- The creators of the **Zomato Restaurant Dataset** used for educational and analytical purposes.
- The open-source Python community for developing excellent data science libraries such as Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and Folium.
- My faculty members and mentors for their continuous guidance and encouragement.

---

# 📌 Project Summary

Restaurant Rating Prediction & Business Analytics is an end-to-end data science project that combines data preprocessing, exploratory data analysis, geospatial analytics, feature engineering, machine learning, and business intelligence to understand restaurant performance and predict customer ratings.

The project demonstrates a complete analytics pipeline and achieved an **R² Score of 0.971** using the Random Forest Regressor, making it a strong portfolio project for Data Science, Machine Learning, and Data Analytics roles.

---

## ⭐ If you like this project, don't forget to give it a Star ⭐

Thank you for visiting this repository!

Happy Learning! 🚀
