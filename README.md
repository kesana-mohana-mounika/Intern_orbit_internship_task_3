# 🌍 Global Terrorism Data Analysis & Attack Type Prediction

This project focuses on analyzing global terrorism data to *identify trends, patterns, and **predict potential attack types* based on historical data. Developed as part of my *Intern Orbit 2-month internship*, the goal is to support counter-terrorism efforts through data-driven insights and modeling.

---

## 📌 Prompt

> *Develop a machine learning model to analyze global terrorism data and identify patterns, trends, and potential future threats.*

---

## 🎯 Objectives

- Preprocess terrorism data for meaningful insights
- Visualize trends in attack types and casualties
- Use clustering (DBSCAN) to discover geographic hotspots
- Train a classifier to predict *attack types* based on inputs like location, time, and casualties
- Build a *future prediction model* to estimate attack types in unseen scenarios

---

## 📊 Dataset

- *Source*: [GTD - Global Terrorism Database (START)](https://www.start.umd.edu/gtd/)
- *Records*: ~180,000+ terror incidents (1970–2017)
- *Selected Features*: Year, Month, Day, Country, Region, Attack Type, Target, Weapon, Latitude, Longitude, Casualties

---

## 🧠 Technologies Used

- *Python*  
- *Libraries*: pandas, numpy, seaborn, matplotlib, scikit-learn, LabelEncoder, DBSCAN, RandomForestClassifier

---

## 📈 Exploratory Data Analysis (EDA)

- 📆 Yearly terror attack frequency
- ⚔️ Average casualties by attack type
- 🗺️ DBSCAN clustering for identifying terror-prone regions based on latitude & longitude

---

## 🔍 ML Modeling: Predicting Attack Types

- *Target Variable*: attacktype1_txt (encoded)
- *Features Used*: Month, Day, Country, Region, Latitude, Longitude, Casualties
- *Model*: RandomForestClassifier (Accuracy ~87%)
- *Encoding*: All categorical columns encoded using LabelEncoder
- *Evaluation*: Confusion Matrix & Classification Report

---


## 📽️ Demo Video

▶️ [Watch the project demo on Google Drive](https://drive.google.com/file/d/VIDEO_ID/view)
---

## 🚀 Future Prediction Demo

We tested a real-world prediction scenario:

```python
Input:
    Date: 19 July
    Country: India
    Region: South Asia
    Latitude: 28.6139
    Longitude: 77.2090
    Casualties: 10

🔮 Predicted Attack Type: Bombing/Explosion (example output)
