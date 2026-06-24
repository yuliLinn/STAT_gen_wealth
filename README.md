## 🚀 Project Overview

This project analyzes patterns of wealth among billionaires using historical data from the **Forbes World’s Billionaires list (1996–2014)**. The dataset, sourced from `billionaires.csv`, was expanded by researchers at the Peterson Institute for International Economics with additional variables describing demographics, wealth origins, and business involvement.

The goal is to explore whether extreme wealth is primarily earned or inherited—and what factors are associated with becoming a billionaire.

---

## 📊 Data Description

* **Dataset:** `billionaires.csv`
* **Time span:** 1996–2014
* **Key variables include:**

  * Net worth (wealth)
  * Age (as of 2014)
  * Gender
  * Wealth origin (inherited vs self-made)
  * Industry / company type

---

## 🔍 Research Questions

### 📈 Linear Regression

* What is the relationship between a billionaire’s **wealth and age**, after controlling for:

  * Gender
  * Whether wealth was inherited
  * Type of company/industry

* How well does this regression model perform on new (test) data?

### 📉 Logistic Regression

* How do **gender, age, and net worth** affect the **log-odds of belonging to the inherited wealth group**?
* How accurately can this model classify individuals on new data?

---

## 🎯 Response Variables

* **Linear Regression:**

  * Predicted net worth of a billionaire based on age and other factors

* **Logistic Regression:**

  * Log-odds of a billionaire’s wealth being inherited

---

## ⚙️ Methods

* Data cleaning and preprocessing
* Linear regression modeling
* Logistic regression modeling
* Model evaluation on training vs. test data

---

## 📊 Key Insights (Expected)

* The relationship between age and wealth may not be strictly linear
* Industry and inheritance likely play a major role in wealth accumulation
* Classification models can help estimate whether wealth is inherited or self-made

---

## 🌍 Why This Matters

Money plays a central role in modern life, and many people wonder whether becoming extremely wealthy is achievable through effort alone.

This project explores a broader question:

> **Is becoming a billionaire attainable through merit, or is it largely driven by inheritance?**

* If most billionaires are **self-made**, this supports the idea of a merit-based system
* If wealth is mostly **inherited**, it suggests extreme wealth may be less accessible

While this analysis is not meant to be predictive for individuals, it offers insight—and a bit of perspective—for anyone curious about reaching the very top of the economic ladder.

---

## 🛠️ Tech Stack

* Python
* Jupyter Notebook
* Pandas / NumPy
* Matplotlib / Seaborn

---

## ⚙️ Getting Started

1. Clone the repository
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:

   ```bash
   jupyter notebook
   ```
