It will include:

Project overview 📝
Dataset info 📊
Setup instructions ⚙️
Exploratory Data Analysis 🔍
Visualizations 📈
Machine Learning (SVM) part 🤖
How to run locally 🚀
Example code snippets 💻

# 🛒 E-Commerce Recommender System using SVM  

## 📌 Overview  
This project analyzes an **E-commerce dataset** and builds a **Support Vector Machine (SVM)** model to recommend & predict user purchase behavior.  

The notebook includes:  
- Data exploration & cleaning  
- Feature understanding (Purchase Price, Job, Email, Credit Card, etc.)  
- Visualizations with `matplotlib` & `seaborn`  
- Training a **Support Vector Machine (SVM)** classifier  
- Insights into customer behavior  

--

## 📂 Dataset  
- File used: `Ecommerce recommender using Support Vector Machine.csv`  
- Shape: **10,000 rows × 14 columns**  
- Key Features:  
  - `Address` 🏠  
  - `Lot` 📦  
  - `AM or PM` ⏰  
  - `Browser Info` 🌐  
  - `Company` 🏢  
  - `Credit Card`, `CC Exp Date`, `CC Security Code`, `CC Provider` 💳  
  - `Email` 📧  
  - `Job` 💼  
  - `Language` 🗣️  
  - `Purchase Price` 💰  

## Required Libraries:
pandas, 
numpy, 
matplotlib, 
seaborn, 
scikit-learn, 

## 🔍 Exploratory Data Analysis (EDA)
Some of the steps performed:
✅ Checking for null values
✅ Finding highest & lowest purchase prices
✅ Analyzing pages viewed
✅ Extracting unique values in columns
✅ Checking correlation matrix

Example:
```python
df.isnull().sum()        # Check missing values
df['Purchase Price'].max()  # Highest Purchase Price
df['Purchase Price'].min()  # Lowest Purchase Price
````

##   📈 Visualizations

The notebook includes plots such as:
Distribution of Purchase Price
Count of AM vs PM transactions
Job vs Purchase Price
Heatmap of correlations

## 📊 Results & Insights

Highest Purchase Price: 💵 Extracted successfully
Lowest Purchase Price: 💵 Extracted successfully
Correlation Analysis: Found relationships between variables

## 📌 Future Work

Improve accuracy with feature engineering 🔧
Try other ML models (Random Forest, XGBoost) 🌲
Deploy recommender system with Flask/Django 🌐
