# 📊 Injustice in the Justice System: Racial Incarcerations and Releases  

### Author: Christopher Kiige  
**Student Number:** 100918296  
**Date:** November 25th, 2024  

---

## 📌 Overview  
This project analyzes **racial disparities in incarceration and release rates** within the United States prison system using the Kaggle dataset [*Prison Population in the US*](https://www.kaggle.com/datasets/konradb/prison-population-in-the-us/data) by Konrad Banachewicz.  

The analysis investigates whether systemic biases exist in the justice system by:  
- Comparing incarceration trends across different races from **2008–2020**  
- Evaluating disparities in **release rates** between White and non-White populations  
- Visualizing these patterns with **graphs and charts**  

This work is motivated by the harmful stereotype that **Black individuals are more likely to commit crimes**, and it seeks to provide a **data-driven perspective** on racial injustice in the legal system.  

---

## ⚙️ Requirements  
To run the notebook/code successfully, install the following dependencies:  

```bash
pip install pandas matplotlib seaborn kagglehub
```
- **pandas** → for data cleaning and aggregation  
- **matplotlib** & **seaborn** → for visualizations  
- **kagglehub** → for downloading the dataset  

---

## 📂 Dataset  
- Source: Kaggle → *Prison Population in the US* (2008–2020)  
- Files used:  
  - `populations_states.csv` → Incarceration data  
  - `admissions_releases_states.csv` → Admissions and release data  

---

## 🛠️ Methodology  
1. **Load and preprocess data**  
   - Filter records after 2008  
   - Convert dates to yearly index  
   - Group by year and compute means  

2. **Analysis**  
   - Incarceration trends by race  
   - Release trends by race  
   - Scatterplots comparing incarceration vs releases  
   - Pie chart showing racial distribution of incarcerations  

3. **Visualization**  
   - Line charts (Incarcerations & releases over time)  
   - Grouped bar charts (Comparisons across races per year)  
   - Scatterplots (Correlations between incarceration & releases)  
   - Pie chart (Total incarcerations by race)  

---

## 📊 Key Findings  
- White individuals make up the **majority of incarcerations**, reflecting population size, but **Black incarceration rates are disproportionately high** relative to their population share.  
- In 2013, Black incarcerations nearly equaled White incarcerations despite the **large population gap**.  
- White individuals are released at a **1.7× higher rate** than non-White individuals.  
- These disparities strongly suggest the presence of **systemic racial bias** in incarceration and release practices.  

---

## 📈 Figures  
- **Figure 1:** Releases by race (line chart)  
- **Figure 2:** Incarcerations by race (line chart)  
- **Figure 3:** Releases by race (bar chart)  
- **Figure 4:** Incarcerations by race (bar chart)  
- **Figure 5:** Scatterplots (incarcerations vs releases)  
- **Figure 6:** Pie chart (total incarcerations by race)  

---

## 📖 References  
- Kaggle Dataset: Konrad Banachewicz, *Prison Population in the US*  
- GeeksforGeeks & Stack Overflow for Pandas/Seaborn methods  
- Seaborn Documentation  
- ChatGPT (OpenAI) for writing refinement and debugging support  

---

## 🚀 How to Run  
1. Clone/download this project.  
2. Install the required libraries.  
3. Download the dataset via `kagglehub`.  
4. Run the notebook or Python script step by step.  
5. View the generated graphs and insights.  
