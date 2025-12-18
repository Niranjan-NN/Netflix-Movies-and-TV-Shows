# 🎬 Netflix Movies & TV Shows – Content Strategy Analysis

## 📌 Project Overview
This project performs an **end-to-end exploratory and analytical study** of Netflix’s Movies and TV Shows catalog to understand content trends, genre popularity, regional distribution, and strategic focus areas.  
The goal is to derive **business-driven insights** that can help Netflix optimize its content acquisition and production strategy.

This project is designed at an **intermediate Data Analyst level**, focusing on data cleaning, feature engineering, visualization, and actionable recommendations.

---

## 🎯 Objectives
- Analyze the growth of Netflix content over time  
- Compare Movies vs TV Shows trends  
- Identify popular genres and content categories  
- Study country-wise and regional content distribution  
- Understand content duration and rating strategy  
- Apply clustering to group similar content types  

---

## 🗂 Dataset Information
- **Source:** Kaggle – Netflix Movies and TV Shows Dataset  
- **Records:** ~8,800 titles  
- **Key Features:**
  - `type` (Movie / TV Show)
  - `title`
  - `director`
  - `cast`
  - `country`
  - `date_added`
  - `release_year`
  - `rating`
  - `duration`
  - `listed_in` (genres)
  - `description`

---

## 🛠 Tools & Technologies
- **Programming Language:** Python  
- **Libraries Used:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Environment:** Jupyter Notebook / Kaggle Notebook  

---

## 📊 Project Workflow

### 1️⃣ Data Cleaning & Preparation
- Removed duplicate records  
- Handled missing values in categorical fields  
- Converted date fields to datetime format  
- Parsed duration into numeric values  
- Standardized genre and country columns  

---

### 2️⃣ Feature Engineering
- Extracted `year_added` and `month_added`
- Separated movie duration and TV show seasons
- Created simplified primary genre feature
- Prepared genre data for clustering

---

### 3️⃣ Exploratory Data Analysis (EDA)
- Movies vs TV Shows distribution
- Year-wise content growth
- Country-wise content contribution
- Top genres on Netflix
- Rating distribution across content types

---

### 4️⃣ Trend & Pattern Analysis
- Growth comparison between Movies and TV Shows over time
- Genre-wise content expansion
- TV show season distribution
- Average movie duration by genre

---

### 5️⃣ Advanced Analysis (Intermediate)
- Multi-label genre encoding
- K-Means clustering to group similar content
- Cluster-based content type comparison

---

## 🔍 Key Insights
- Netflix significantly increased **TV Show production after 2016**, focusing on long-term engagement  
- **Drama, Comedy, and International content** dominate the catalog  
- The **TV-MA rating** is the most common, indicating a strong adult audience focus  
- A small set of genres contributes to a large portion of content  
- Regional content (India, South Korea, Spain) shows strong growth potential  

---

## 💡 Business Recommendations
- Increase investment in **regional and international TV shows**
- Optimize content strategy by reducing low-performing genres
- Maintain a balance between short and multi-season content
- Continue expanding high-demand genres like Drama and International TV
- Use clustering insights to personalize content recommendations

---

## 📁 Project Structure
Netflix-Data-Analysis/
│
├── 01_data_cleaning_eda.ipynb
├── 02_content_trends_genre_analysis.ipynb
├── 03_business_insights_recommendations.ipynb
└── README.md


---

## 🚀 Future Improvements
- Time-series forecasting for content growth
- Sentiment analysis on content descriptions
- Interactive dashboard using Power BI / Tableau
- Recommendation system based on content similarity

---

## 👤 Author
**Niranjan NN**  
Aspiring Data Analyst | Kaggle Contributor  
- GitHub: https://github.com/Niranjan-NN  
- Kaggle: https://www.kaggle.com/  

---
