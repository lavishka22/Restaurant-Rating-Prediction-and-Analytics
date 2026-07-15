# Restaurant Rating Prediction & Analytics

A machine learning project that predicts restaurant ratings with high accuracy using Python, EDA, feature engineering, and advanced data visualization techniques. Achieved **R² = 0.971** on the prediction model.

---

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Model Performance](#model-performance)
- [Usage](#usage)
- [Results & Insights](#results--insights)
- [Contributing](#contributing)
- [License](#license)

---

## 🎯 Overview

This project leverages machine learning and data science techniques to predict restaurant ratings based on various features. Through comprehensive exploratory data analysis (EDA) and feature engineering, we built a high-performing predictive model that can help understand key factors influencing restaurant ratings.

**Key Achievement:** R² Score of **0.971** indicating excellent model fit and prediction accuracy.

---

## ✨ Features

- **Exploratory Data Analysis (EDA)** – Comprehensive statistical and visual analysis of restaurant data
- **Feature Engineering** – Creation and transformation of features to improve model performance
- **Multiple ML Models** – Testing and comparison of various algorithms
- **Data Visualization** – Interactive and publication-ready visualizations
- **High Accuracy** – R² = 0.971 demonstrating excellent predictive capability
- **Scalable Pipeline** – Reproducible and modular code structure

---

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip or conda package manager

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/lavishka22/Restaurant-Rating-Prediction-and-Analytics.git
   cd Restaurant-Rating-Prediction-and-Analytics
   ```

2. **Create a virtual environment (recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## 📁 Project Structure

```
Restaurant-Rating-Prediction-and-Analytics/
├── data/                      # Dataset files
│   ├── raw/                   # Original data
│   └── processed/             # Cleaned data
├── notebooks/                 # Jupyter notebooks
│   ├── 01_eda.ipynb          # Exploratory Data Analysis
│   ├── 02_feature_engineering.ipynb
│   └── 03_modeling.ipynb     # Model training & evaluation
├── src/                       # Source code
│   ├── preprocessing.py      # Data cleaning functions
│   ├── feature_engineering.py # Feature creation
│   ├── models.py             # ML model implementations
│   └── visualization.py      # Plotting utilities
├── results/                   # Output results
│   ├── models/               # Trained model files
│   └── plots/                # Generated visualizations
├── requirements.txt          # Python dependencies
├── README.md                 # This file
└── LICENSE                   # MIT License
```

---

## 📊 Dataset

- **Source:** [Specify your data source]
- **Records:** [Number of samples]
- **Features:** [Total number of features]
- **Target Variable:** Restaurant Rating

### Key Features Include:
- Restaurant location and type
- Cuisine type(s)
- Price range
- Service quality metrics
- Amenities and facilities
- Customer reviews & feedback
- [Add other relevant features]

---

## 🤖 Model Performance

### Models Tested
- Linear Regression
- Random Forest
- Gradient Boosting
- Support Vector Machines (SVM)
- Neural Networks

### Best Model Performance Metrics

| Metric | Score |
|--------|-------|
| **R² Score** | **0.971** |
| RMSE (Root Mean Squared Error) | [Value] |
| MAE (Mean Absolute Error) | [Value] |
| Cross-Validation Score | [Value] |

### Performance Comparison
[Include a visualization or table comparing all models tested]

---

## 💻 Usage

### Basic Prediction Example

```python
from src.models import load_model, preprocess_features

# Load the trained model
model = load_model('results/models/best_model.pkl')

# Prepare restaurant features
features = {
    'location': 'Downtown',
    'cuisine_type': 'Italian',
    'price_range': 3,
    'seating_capacity': 120,
    # ... other features
}

# Predict rating
predicted_rating = model.predict([preprocess_features(features)])
print(f"Predicted Rating: {predicted_rating[0]:.2f}")
```

### Running the Full Pipeline

```bash
# Run EDA
jupyter notebook notebooks/01_eda.ipynb

# Feature Engineering
jupyter notebook notebooks/02_feature_engineering.ipynb

# Model Training & Evaluation
jupyter notebook notebooks/03_modeling.ipynb
```

---

## 📈 Results & Insights

### Key Findings from EDA
- [Insight 1: Most important factor affecting ratings]
- [Insight 2: Distribution patterns]
- [Insight 3: Correlation discoveries]

### Feature Importance
The top 5 most important features for prediction:
1. [Feature 1] – [Importance %]
2. [Feature 2] – [Importance %]
3. [Feature 3] – [Importance %]
4. [Feature 4] – [Importance %]
5. [Feature 5] – [Importance %]

### Visualizations
- Distribution of restaurant ratings
- Feature correlations heatmap
- Model prediction accuracy plots
- Residual analysis
- Feature importance rankings

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

Please ensure your code follows PEP 8 style guidelines and includes appropriate documentation.

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**lavishka22**  
GitHub: [@lavishka22](https://github.com/lavishka22)

---

## 🙏 Acknowledgments

- Thanks to [data source/contributors]
- Inspired by [relevant projects/papers]

---

**Last Updated:** July 2026
