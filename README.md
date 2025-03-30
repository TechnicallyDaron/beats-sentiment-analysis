# 🗂️ Sentiment Analysis of Amazon Speaker Reviews

## 🔍 Overview  
This project analyzes customer sentiment toward wireless speakers by scraping and processing Amazon reviews. Using Python libraries like **Pandas**, **NumPy**, and **TextBlob**, the goal was to extract insights into what customers love (or don’t love) about the product — helping brands like Beats by Dre better understand their audience.

---

## 📈 Features  
- Web-scraped Amazon product reviews  
- Cleaned and preprocessed text data  
- Performed **Exploratory Data Analysis (EDA)** using Pandas  
- Conducted **Sentiment Analysis** using TextBlob  
- Visualized results with Matplotlib & Seaborn  
- Explored key EDA topics: product features, pricing feedback, endorsements

---

## 🛠️ Tools & Libraries  
- Python  
- Pandas  
- NumPy  
- TextBlob  
- Matplotlib  
- Seaborn  
- Google Colab

---

## 📊 Sample Insights  
- Majority of customer reviews were **positive**, focusing on sound quality and portability  
- Negative reviews often mentioned **connectivity issues** and **battery life**  
- Identified top keywords from positive/negative sentiments to help with product positioning

## 📈 Interactive Dashboard (Claude)

You can explore the interactive dashboard created for this project here:  
🔗 [Beats Sentiment Analysis Dashboard (Claude)](https://claude.site/artifacts/b37fc175-d897-4612-b84d-7080c066fee8)

This dashboard was built using Claude and visualizes survey findings, product insights, and customer sentiment in a clean format for business stakeholders.

---

## 💻 How to Run
1. Clone the repo or open the notebook in Google Colab  
2. Install dependencies (if running locally):  

```
pip install pandas numpy textblob matplotlib seaborn
``` 

3. Run each Python script or notebook file in sequence to follow the data pipeline:
   - `copy_of_json_reviews_to_dataframe.py` (load reviews)
   - `pandas.py`, `p3_s4_3.py`, etc. (EDA + sentiment code)
   - `p3_s4_12.py` (TextBlob sentiment + final analysis)

---

## 📌 What I Learned  
- How to clean and analyze real-world, unstructured text data  
- How to apply NLP tools like **TextBlob** for polarity and subjectivity scoring  
- How to visualize data in a way that tells a clear story  
- How to go from raw text to actual business insights

---

## 🚀 Future Improvements  
- Automate data scraping  
- Integrate social media reviews (Twitter, Reddit)  
- Try more advanced NLP tools like **VADER** or **spaCy**



 
