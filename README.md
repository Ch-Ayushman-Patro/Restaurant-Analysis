# 🍽️ Restaurant Analysis

**Project date:** March 3, 2024  
**Notebook / dataset:** `Restaurant Dataset.csv`  
**Rows:** 9,551 | **Columns:** 21  

A detailed exploratory data analysis (EDA) project that explores restaurants from different countries — focusing on cuisines, locations, price ranges, delivery options, and customer ratings.

---

## 📊 Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset Summary](#dataset-summary)
3. [Key Findings](#key-findings)
4. [Exploratory Analyses & Visualizations](#exploratory-analyses--visualizations)
5. [How to Run the Notebook](#how-to-run-the-notebook)
6. [Requirements](#requirements)
7. [Next Steps](#next-steps)
8. [Files](#files)
9. [Contact & License](#contact--license)

---

## 🧠 Project Overview
This project performs an exploratory data analysis on a dataset of global restaurants containing information about:
- Locations and coordinates  
- Cuisines served  
- Pricing and currency  
- Ratings and votes  
- Online delivery and booking options  
- Restaurant chains and popularity  

The analysis answers questions such as:
- What cuisines are most common?  
- Which cities have the most restaurants and best ratings?  
- How do price ranges and delivery options affect ratings?  
- Which restaurant chains dominate the dataset?

---

## 📁 Dataset Summary

**File:** `Restaurant Dataset.csv`  
**Total Records:** 9,551  
**Total Columns:** 21  

| Column Name | Description |
|--------------|-------------|
| Restaurant ID | Unique ID for each restaurant |
| Restaurant Name | Name of the restaurant |
| Country Code | Numeric country identifier |
| City | City name |
| Longitude / Latitude | Location coordinates |
| Cuisines | Cuisine types (can be multiple) |
| Average Cost for two | Cost for two people |
| Currency | Currency symbol |
| Has Table booking / Online delivery | Yes / No flags |
| Price range | 1–4 (budget to premium) |
| Aggregate rating | Average customer rating |
| Votes | Number of user votes |

- Missing values only in **Cuisines** (9 rows)  
- `Aggregate rating` ranges from **0.0 → 4.9**  
- Mean votes per restaurant ≈ **157**

---

## 📈 Key Findings

- **Top 3 cuisines:**
  1. North Indian — *936 restaurants* (≈ 9.8 %)  
  2. North Indian, Chinese — *511 restaurants* (≈ 5.35 %)  
  3. Chinese — *354 restaurants* (≈ 3.7 %)

- **City with most restaurants:** `New Delhi`  
- **City with highest average rating:** `Inner City`  
- **Price range distribution:**  
  - 1 → 46.53 %  
  - 2 → 32.59 %  
  - 3 → 14.74 %  
  - 4 → 6.14 %

- **Online delivery availability:**  
  - Yes → 25.66 %  
  - No → 74.34 %

- **Average rating comparison:**  
  - Online delivery = 3.25  
  - No online delivery = 2.46  

- **Top restaurant chains:**  
  - Cafe Coffee Day (83)  
  - Domino’s Pizza (79)  
  - Subway (63)  
  - McDonald’s (48)

---

## 🧮 Exploratory Analyses & Visualizations

### 🔹 Load and inspect data
```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
import plotly.express as px

ds = pd.read_csv('Restaurant Dataset.csv')
ds.info()
ds.head()
