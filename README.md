# 📊 EDA - 1 (Google Play Store Data)

Welcome to my first Exploratory Data Analysis (EDA) project! In this notebook, I have performed a detailed EDA on the **Google Play Store dataset**, uncovering key insights and cleaning the data for further machine learning tasks.

---

## 📁 Dataset Overview

The dataset contains information about apps available on the Google Play Store, including:

- App name
- Category
- Rating
- Number of installs
- Type (Free/Paid)
- Price
- Size
- Content rating
- Genres
- Last updated
- Current version
- Android version

---

## 🛠️ Tasks Performed

### ✅ Data Cleaning
- Handled missing values
- Fixed data types
- Cleaned columns like Size, Installs, and Price
- Removed duplicates and invalid entries

### ✅ Univariate Analysis
- Distribution of app ratings
- Most common app categories
- Distribution of app sizes and installs

### ✅ Bivariate/Multivariate Analysis
- Relationship between app rating and number of installs
- Price comparison across categories
- Category-wise average ratings

### ✅ Outlier Detection & Handling
- Identified and capped/remediated outliers in numerical columns

### ✅ Visualizations
- Histograms, box plots, scatter plots, bar charts
- Heatmaps for correlation matrix

---

## 📌 Key Insights

- Free apps dominate the Play Store.
- Most apps have a rating between 4.0 and 4.5.
- Categories like **Games** and **Tools** are the most populated.
- Paid apps tend to have slightly higher ratings.
- App size does not strongly correlate with rating.

---

## 📎 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

---

# 🍷 EDA - 2 (Red Wine Quality Dataset)

Welcome to my second Exploratory Data Analysis (EDA) project! In this notebook, I have analyzed an **Red Wine Quality Dataset** In this project, I analyzed the Red Wine Quality dataset to understand chemical properties affecting wine quality.

---

## 📁 Dataset Overview

The dataset contains physicochemical properties such as:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Sulphates
- Alcohol
- pH
- Quality (target variable)
---

## 🛠️ Tasks Performed

- Checked data distribution
- Analyzed correlation between features
- Identified influential features affecting wine quality
- Performed outlier analysis
- Generated correlation heatmaps
- Compared feature distributions across quality levels

---

## 📌 Key Insights

- Alcohol content positively correlates with wine quality.
- Volatile acidity negatively impacts quality.
- Some features show strong inter-correlation.
- The dataset has class imbalance in quality ratings.

---

## 📎 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook  

---

# 📊 EDA - 3 (Chronic Disease Dataset)

Welcome to my third Exploratory Data Analysis (EDA) project! In this notebook, I have worked with a **Chronic Disease dataset**, analyzing patient-related features to discover patterns and potential indicators related to chronic conditions.

---

## 📁 Dataset Overview

The dataset includes health and lifestyle-related information such as:

- Age  
- Gender  
- Blood Pressure  
- Cholesterol Level  
- Glucose Level  
- Smoking, Alcohol, Physical Activity  
- BMI  
- Presence of Chronic Disease (Target Variable)

---

## 🛠️ Tasks Performed

### ✅ Data Cleaning
- Checked for missing values and handled them  
- Verified data types and converted where necessary  
- Removed or corrected inconsistent records

### ✅ Univariate Analysis
- Distribution of numerical variables (e.g., age, BMI)  
- Frequency of categorical features (e.g., gender, smoking status)  
- Count of patients with and without chronic disease

### ✅ Bivariate Analysis
- Relationship between lifestyle habits and chronic disease  
- Distribution of disease status across age groups  
- Impact of glucose and cholesterol levels on health condition

### ✅ Multivariate Analysis
- Combined multiple features (e.g., age, lifestyle, medical history)  
- Heatmap and pairplots to identify key patterns  
- Correlation between features influencing chronic disease

### ✅ Visualizations
- Histograms, bar plots, count plots  
- Box plots and violin plots for distributions  
- Heatmaps and scatter matrices

---

## 📌 Key Insights

- Higher glucose and cholesterol levels are common among chronic disease patients  
- Lifestyle habits like smoking and lack of physical activity contribute to chronic conditions  
- Certain age groups show higher disease prevalence  
- Gender differences are notable in some health indicators

---

## 📎 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook

---




# ✈️ EDA - 4 (Flight Price Dataset)

Welcome to my fourth Exploratory Data Analysis (EDA) project! In this notebook, I have worked with a **Flight Price Dataset** This project focuses on airline ticket price prediction data.
---

## 📁 Dataset Overview

The dataset includes information such as:

- Airline
- Date of Journey
- Source
- Destination
- Duration
- Total Stops
- Additional Info
- Price (target)

---

## 🛠️ Tasks Performed

### ✅ Data Cleaning
- Converted duration into minutes
- Extracted journey day/month
- Cleaned categorical features
- Handled missing values

### ✅ Feature Engineering
- Created time-based features=
- Encoded categorical variables
- Converted stops to numerical format

### ✅ EDA
- Airline-wise price comparison
- Source-destination analysis
- Price variation based on stops
- Duration vs price relationship

---

## 📌 Key Insights
- Flights with more stops are generally cheaper.
- Airline brand significantly impacts price.
- Duration moderately correlates with price.
- Certain routes are consistently expensive.
---

## 📎 Tools Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook

---
### 🎯 Skills Demonstrated
- Data Cleaning
- Handling Missing Values
- Outlier Detection
- Feature Engineering
- Data Visualization
- Correlation Analysis
- Insight Extraction
- Preparing data for ML

---
### 📌Future Improvements
- Add ML models after EDA
- Build Streamlit dashboards
- Deploy insights as web apps



