# 🏅 Generative AI Final Project – Olympic Medal Analysis

This project was developed as a final assignment for the **Generative AI for Data Science** course.

---

## 📁 Dataset  
- **Source:** Kaggle – [120 years of Olympic history: athletes and results](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)  
- **Size:** Over 270,000 athlete event records  
- **Target variables:** Medal (Gold, Silver, Bronze)  
- **Features include:** Year, Sport, Event, Sex, Age, Height, Weight, Country (NOC)

---

## 🔍 Project Objectives  
- Use Generative AI to support data cleaning, analysis, and visualization  
- Perform Exploratory Data Analysis (EDA)  
- Analyze athlete participation, medal trends, and gender differences  
- Compare **Linear**, **Polynomial**, and **Ridge Regression** models  
- Use **Box plots** and **Bar charts** to enhance visual storytelling  
- Evaluate model performance and limitations

---

## 📊 Project Files

| File                     | Description                                                |
|--------------------------|------------------------------------------------------------|
| `athlete_events.csv`     | Raw dataset from Kaggle                                    |
| `olympic_analysis.ipynb` | Jupyter Notebook containing all code, graphs, and models   |
| `chat.txt`               | Full transcript of AI prompts and responses during project |

---

## 📦 Models Used

- **Linear Regression** (Univariate and Multivariate)
- **Polynomial Regression** (degree = 2)
- **Ridge Regression** with hyperparameter tuning via Grid Search
- Classification model (Logistic Regression) to estimate medal probability

---

## 📈 Key Insights & Results

- Athlete participation and number of events have increased over time  
- Medal counts vary by year, gender, and country  
- Ridge Regression achieved the best prediction performance (lowest error, highest R²)  
- Box plots revealed meaningful age distributions by gender  
- Generative AI was instrumental in creating visualizations, tuning models, and writing code logic  

---

## 📎 Submission

All required files were submitted via **MyFire** and documented in this GitHub repository as required by the course.

---

# 🏅 Olympic Medal Analysis – Generative AI Final Project

This project was developed as the final assignment for the **Generative AI for Data Science** course, focusing on data exploration, visualization, and predictive modeling using historical Olympic data from 1896 to 2016.

---

## 📁 Dataset

- **Source:** Kaggle – Olympic History Dataset
- **Size:** Over 120,000 athlete event records
- **Target Variable:** Medal (Gold, Silver, Bronze, or None)
- **Key Features:** Age, Height, Weight, Gender, NOC (country), Year, Sport, and Event

---

## 🔍 Objectives

- Use generative AI to assist in code development and exploration
- Perform data cleaning and exploratory data analysis (EDA)
- Visualize trends in medal distribution, athlete age, and national performance
- Build and evaluate models to predict medal outcomes based on physical attributes

---

## 📊 Project Files

| File              | Description                                      |
|-------------------|--------------------------------------------------|
| `data.csv`    | Raw dataset used in the analysis                 |
| `analysis.ipynb` | Jupyter notebook with complete analysis and modeling |
| `chat.txt`        | Transcript of interactions with generative AI   |

---

## 📈 Models Used

- Logistic Regression (with class weighting)
- Polynomial Ridge Classifier (degree = 2)

---

## ✅ Key Results

- The Ridge Classifier outperformed Logistic Regression in recall and precision.
- Visualizations revealed consistent trends in average medalist age and dominance by countries like the USA and URS.
- AI tools helped streamline EDA, code debugging, and final presentation formatting.

---

## 💡 Insights

### 📌 Key Findings:
- Global athlete participation grew steadily over time.
- Female representation increased substantially, nearing parity in recent editions.
- Many medalists compete across multiple Olympic editions, indicating career longevity.
- Medalists typically fall within specific age, height, and weight ranges.

### 🧠 Machine Learning Notes:
- Ridge Classifier captured nonlinear interactions and performed better on minority classes.
- Still, physical attributes alone were not sufficient to predict medals reliably.

---

## ⚠️ Limitations

- Data had missing values (e.g., height/weight), reducing modeling accuracy.
- Psychological and training variables were unavailable.

---

## 🔮 Future Work

- Integrate external data (training hours, injury history, etc.)
- Explore time-series models for medal predictions.
- Use clustering to identify athlete profiles by sport.

---

This project demonstrates the power of combining data science with generative AI to uncover trends and build predictive models from historical datasets.