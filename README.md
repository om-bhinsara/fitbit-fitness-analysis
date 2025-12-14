# **Fitbit Fitness & Activity Analysis**

## 📌 Project Overview

This project performs exploratory data analysis (EDA) on Fitbit fitness tracker data to understand how **physical activity, sleep behavior, sedentary time, and calorie expenditure** are related in real-world health data.

---

## 🎯 Objectives

* Analyze the relationship between **daily steps and calories burned**
* Study the impact of **activity levels on energy expenditure**
* Examine how **sleep duration and sleep efficiency relate to activity**
* Analyze **sedentary behavior patterns**
* Practice handling **missing and incomplete real-world health data**

---

## 📊 Dataset

**Source:** Fitbit Fitness Tracker Data (Kaggle)

**Features include:**

* Daily steps and distance
* Active and sedentary minutes
* Calories burned
* Sleep duration and time in bed
* Limited heart-rate data (not used for core analysis)

---

## 🛠 Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🔍 Key Insights

* Daily steps and calories show a **moderate positive relationship**, indicating that increased activity leads to higher energy expenditure.
* **Activity level** is a strong determinant of calorie burn, with highly active days burning significantly more calories than sedentary days.
* **Sleep duration does not strongly predict physical activity**, suggesting that longer sleep may reflect recovery or low-activity days.
* **Sleep efficiency does not consistently improve with higher activity levels**, highlighting the complex interaction between rest and movement.
* **Sedentary behavior and sleep duration show no meaningful relationship**.

---

## 📁 Project Structure

```
📦 fitbit-fitness-analysis
┣ 📂 data
┃ ┣ 📂 raw
┃ ┗ 📂 processed
┣ 📂 notebook
┃ ┗ 📄 fitness_health_analysis.ipynb
┣ 📄 README.md
┣ 📄 requirements.txt
┗ 📄 .gitignore
```

---

## ⚠️ Limitations

* Sleep data is available only for days when users tracked sleep.
* Heart-rate data exists for only **8 user-day records**, which is insufficient for meaningful analysis.
* Heart-rate-based insights were excluded to avoid unreliable conclusions.

---

## ✅ Conclusion

This analysis demonstrates that **consistent physical activity plays a more significant role in calorie expenditure than sleep duration alone**, while sleep quality and activity exhibit a complex relationship. The project highlights the importance of thoughtful data cleaning, domain-aware analysis, and responsible interpretation when working with real-world fitness datasets.
