# 📊 CodeAlpha Data Analytics Internship Project  
## 🛒 Amazon Reviews Analytics

### 👨‍💻 Intern: Ali Ashar  
BS Artificial Intelligence | Data Analytics Intern  

---

## 🎥 Project Explanation Video

A complete walkthrough of this project is available in the repository:

📽️ **Project_Explaination.mp4**

The video covers:
- Project overview
- Dataset explanation
- EDA insights
- Data visualizations
- Sentiment analysis implementation
- Model performance discussion

---

## 📖 Project Overview

This project was completed as part of the CodeAlpha Data Analytics Internship.

The objective was to analyze Amazon product reviews and extract meaningful insights using data analytics and machine learning techniques.

The project integrates:

- Web Scraping (Conceptual Implementation)
- Exploratory Data Analysis (EDA)
- Data Visualization
- Sentiment Analysis using Machine Learning

This notebook demonstrates an end-to-end data analytics workflow from raw data preprocessing to predictive modeling.

---

## 📂 Dataset Information

The dataset contains Amazon product review data including:

- Brand
- Product Price
- Review Rating
- Review Text
- Review Date
- Helpful Votes

After cleaning:
- 1177 valid review records were used for EDA
- A balanced dataset was created for sentiment analysis

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression

---

## ✅ Task 1: Web Scraping (Conceptual)

Explained how review data can be scraped from Amazon using:

- Requests (HTTP requests)
- BeautifulSoup (HTML parsing)
- Data extraction and CSV storage

The dataset used in this project represents structured data that would be obtained after scraping.

---

## ✅ Task 2: Exploratory Data Analysis (EDA)

Performed data cleaning and analysis to understand customer behavior.

### Key Steps:

- Removed missing ratings
- Converted rating to integer format
- Extracted numeric price from JSON structure
- Converted review dates to datetime format
- Analyzed yearly rating trends
- Evaluated helpful vote distribution

### 📊 Key Insights:

- Majority of reviews are 5-star ratings.
- Ratings dipped around 2014 and improved afterward.
- Higher-priced products tend to receive better ratings (up to 4 stars).
- 2-star and 3-star reviews receive the highest average helpful votes.

---

## ✅ Task 3: Data Visualization

Created meaningful visualizations to support insights:

- Rating distribution bar chart
- Average price by rating
- Rating trend over time
- Helpful votes comparison
- Confusion matrix for model evaluation

These visuals transform raw data into interpretable business insights.

---

## ✅ Task 4: Sentiment Analysis

Built a machine learning model to classify reviews as Positive or Negative.

### Process:

1. Text cleaning and preprocessing
2. Removed neutral (3-star) reviews
3. Created binary sentiment labels
4. Balanced dataset using downsampling
5. Applied TF-IDF vectorization
6. Trained Logistic Regression model
7. Evaluated using accuracy, precision, recall, F1-score

---

## 🤖 Model Performance

- Balanced dataset: 152 samples
- Model: Logistic Regression
- Accuracy Achieved: **74%**

The model demonstrated stable classification performance across both classes.

---

## 🚀 Project Outcome

This project demonstrates practical implementation of:

- Data preprocessing
- Statistical analysis
- Data visualization
- Natural Language Processing (NLP)
- Machine Learning modeling

It reflects a real-world data analytics workflow from raw data to predictive insights.

---

## 🔗 Author

Ali Ashar  
BS Artificial Intelligence  
Data Analytics Intern at CodeAlpha
