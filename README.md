# 📊 CodeAlpha Data Analytics Internship Project  
## 🛒 Amazon Reviews Analytics

### 👨‍💻 Intern: Ali Ashar  
BS Artificial Intelligence | Data Analytics Intern  

---

## 📖 Project Overview

This project was completed as part of the CodeAlpha Data Analytics Internship.  

The objective of this project was to analyze Amazon product reviews and extract meaningful insights using data analytics and machine learning techniques.

The project integrates:

- Web Scraping (Conceptual Explanation)
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

## ✅ Task 1: Web Scraping (Conceptual Implementation)

The project explains how review data can be collected from Amazon using:

- `requests` for sending HTTP requests
- `BeautifulSoup` for parsing HTML
- Extraction of:
  - Review Text
  - Rating
  - Price
  - Date

The provided dataset represents the structured data that would be obtained after scraping.

---

## ✅ Task 2: Exploratory Data Analysis (EDA)

The dataset was cleaned and analyzed to understand customer behavior.

### Key EDA Steps:

- Removed missing ratings
- Converted rating to integer
- Extracted numeric price from JSON format
- Converted review date to datetime format
- Created yearly trend analysis

### 📊 Insights from EDA:

- Majority of reviews were 5-star ratings.
- Ratings showed a slight dip around 2014 but improved afterward.
- Higher-priced products tended to receive better ratings (up to 4 stars).
- 2-star and 3-star reviews received the highest average helpful votes.

---

## ✅ Task 3: Data Visualization

Multiple visualizations were created to support analytical insights:

- Rating distribution bar chart
- Average price by rating
- Rating trend over time (line plot)
- Helpful votes vs rating comparison
- Confusion matrix for model evaluation

These visualizations help transform raw data into meaningful business insights.

---

## ✅ Task 4: Sentiment Analysis

A machine learning model was built to classify reviews as Positive or Negative.

### 🔹 Steps Performed:

1. Text cleaning (lowercasing, removing punctuation)
2. Removed neutral (3-star) reviews
3. Created binary sentiment labels:
   - 4–5 stars → Positive
   - 1–2 stars → Negative
4. Balanced dataset using downsampling
5. Applied TF-IDF vectorization
6. Trained Logistic Regression model
7. Evaluated performance using:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix

---

## 🤖 Model Performance

- Dataset balanced: 152 samples
- Model Used: Logistic Regression
- Accuracy Achieved: **74%**

The model demonstrated stable performance across both positive and negative classes.

---

## 📌 Key Takeaways

- Customer reviews are predominantly positive.
- Mid-range reviews (2–3 stars) provide more helpful insights.
- Product pricing influences ratings but not strictly linearly.
- Sentiment analysis can effectively classify customer opinion using NLP techniques.

---

## 🚀 Project Outcome

This project demonstrates practical implementation of:

- Data cleaning and preprocessing
- Statistical exploration
- Data visualization
- Natural Language Processing (NLP)
- Machine Learning model building

It reflects real-world data analytics workflow and business insight extraction.

---

## 🔗 Author

Ali Ashar  
BS Artificial Intelligence  
Data Analytics Intern at CodeAlpha
