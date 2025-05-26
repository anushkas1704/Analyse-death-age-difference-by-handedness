# 🧠 Handedness and Lifespan Analysis

This project explores the correlation between **handedness** (left-handed vs. right-handed) and **lifespan trends** using real-world data from National Geographic and US Death Distribution statistics. The analysis is carried out using **Python**, leveraging libraries like **Pandas**, **NumPy**, and **Matplotlib**.

> 📍 Completed during the **Data Analytics Traineeship at MedTourEasy**, along with training in Python, R, SQL, and Tableau.

---

## 📌 Objective

To model the probability of being left- or right-handed across different ages and estimate how handedness correlates with **mean age at death**, using probabilistic modeling and historical data trends.

---

## 📂 Dataset Sources

- **National Geographic Handedness Survey (1986)** — gender-wise left-handedness data by age
- **US Death Distribution Data** — mortality counts by age

---

## 🔧 Tools & Libraries Used

- Python 3.x
- pandas
- numpy
- matplotlib

---

## 📊 Tasks Overview

Each task in the notebook corresponds to a major analysis step:

### ✅ Task 1: Data Loading & Visualization
- Loaded handedness data and created basic scatter plots of male/female left-handedness vs. age.
- 📍 *Graph Placeholder*: `scatter_male_female_age.png`

### ✅ Task 2: Birth Year Mapping and Mean Handedness
- Calculated birth year (`1986 - age`) and average left-handedness.
- Visualized the trend of mean left-handedness across birth years.
- 📍 *Graph Placeholder*: `mean_lh_vs_birth_year.png`

### ✅ Task 3: Estimating Conditional Probability P(LH|A)
- Defined probabilities of being left-handed given age using data from early and late 1900s.

### ✅ Task 4: US Death Distribution Plot
- Loaded US death data and plotted number of deaths per age.
- 📍 *Graph Placeholder*: `death_distribution.png`

### ✅ Task 5: P(LH) — Overall Probability of Left-Handedness
- Combined death and handedness data to estimate the overall population-level probability of being left-handed.

### ✅ Task 6: P(A|LH) — Probability of Dying at Age A, Given Left-Handedness
- Used Bayes' theorem to compute this conditional probability.

### ✅ Task 7: P(A|RH) — Same as Task 6, for Right-Handedness

### ✅ Task 8: Visualization of Probabilities by Age
- Plotted P(A|LH) and P(A|RH) side by side for visual comparison.
- 📍 *Graph Placeholder*: `probability_plots_lh_rh.png`

### ✅ Task 9: Mean Lifespan Comparison
- Calculated and compared average lifespan of left-handers vs right-handers.
- 📌 Finding: Left-handed people had an estimated **X-year** shorter lifespan (based on modeled data).

### ✅ Task 10: Recalculation for Modern Study Year (2018)
- Repeated analysis assuming a more recent year to observe temporal effects.

---

## 📈 Key Insights

- Average left-handedness rates varied **~50%** between early and late 1900s.
- Modeled difference in lifespan was up to **5–9 years** between handedness types (depending on study year).
- Demonstrated use of **Bayesian probability** and real demographic data to simulate population traits.

---
