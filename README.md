# OTT-First-Day-Viewership-Analysis
“Analysis and prediction of OTT platform content viewership"
# 🎬 ShowTime OTT Platform – First-Day Viewership Analysis

This project aims to analyze and predict the **first-day content viewership** on the ShowTime OTT platform using **Exploratory Data Analysis (EDA)** and **Linear Regression modeling**. 

With the rising popularity of OTT platforms, understanding what factors influence viewership can help businesses make data-driven decisions on content strategy, release timing, and marketing investments.

---

## 📌 Objective

ShowTime, an OTT service provider, wants to identify key variables that impact **first-day viewership** for movies and web series. This includes analyzing variables such as ad impressions, trailer views, genre, day of the week, and more — to uncover insights and build a predictive model using **linear regression**.

---

## 📁 Dataset Description

The dataset contains the following features:

| Column             | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `visitors`         | Average number of platform visitors (in millions) in the past week         |
| `ad_impressions`   | Number of ad impressions (in millions) across campaigns                    |
| `major_sports_event` | Whether a major sports event was scheduled on the content's release day    |
| `genre`            | Genre of the content (e.g., Drama, Action, Comedy)                         |
| `dayofweek`        | Day of the week the content was released                                   |
| `season`           | Season of release (e.g., Winter, Summer)                                   |
| `views_trailer`    | Trailer views (in millions)                                                 |
| `views_content`    | First-day views of the content (target variable, in millions)              |

---

## 📊 Exploratory Data Analysis (EDA)

In this section, the dataset was explored to find patterns, trends, and correlations.

### Key Questions Answered:
- 📈 What does the distribution of content views look like?
- 🎭 What does the distribution of genres look like?
- 📆 How does viewership vary with the **day of release**?
- ❄️ How does viewership vary with the **season**?
- 🔁 What is the correlation between **trailer views** and **content views**?
- ➕ Additional insights from categorical and numerical feature relationships

---

## 🤖 Machine Learning Model

- A **Linear Regression** model was built to predict the first-day viewership.
- Key model features included: `ad_impressions`, `views_trailer`, `dayofweek`, `season`, etc.
- The model was evaluated using metrics like **R² score**, **RMSE**, and **MAE**.

---

## 📌 Tools & Technologies Used

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn** (for EDA & visualization)
- **Scikit-learn** (for linear regression modeling)
- **Jupyter Notebook**

---

## ✅ Outcomes

- Identified the most influential variables driving first-day views
- Quantified the relationship between trailer views and actual content performance
- Created a data-driven base for **release planning and marketing optimization**

---

## 🧠 Learnings

- Strengthened understanding of feature selection and multicollinearity handling  
- Gained hands-on experience in building and evaluating regression models  
- Practiced storytelling through data using plots and model interpretations

---

## 📌 Author

**Sufiyan B**  
[LinkedIn](https://www.linkedin.com/in/syed-sufiyan-32995b232)

---

