<div align="center">

# 🍽️ Restaurant Analysis

### Comprehensive Exploratory Data Analysis of Restaurant Trends

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)](https://pandas.pydata.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

[Overview](#-overview) • [Key Insights](#-key-insights) • [Installation](#-installation) • [Usage](#-usage) • [Visualizations](#-visualizations) • [Contact](#-contact)

</div>

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Dataset Description](#-dataset-description)
- [Key Insights](#-key-insights)
  - [Cuisine Analysis](#-cuisine-analysis)
  - [City and Ratings](#-city-and-ratings)
  - [Pricing Trends](#-pricing-trends)
  - [Online Delivery Impact](#-online-delivery-impact)
  - [Ratings & Popularity](#-ratings--popularity)
  - [Restaurant Chains](#-restaurant-chains)
- [Visualizations](#-visualizations)
- [Tech Stack](#-tech-stack)
- [Installation](#-installation)
- [Usage](#-usage)
- [Project Structure](#-project-structure)
- [Contributing](#-contributing)
- [Contact](#-contact)

---

## 🎯 Overview

This project presents a comprehensive **Exploratory Data Analysis (EDA)** of a restaurant dataset containing **9,551 restaurants** across multiple cities. The analysis uncovers valuable insights into:

- 🍜 **Cuisine popularity** and diversity
- ⭐ **Restaurant ratings** and their distribution
- 🏙️ **City-wise restaurant** presence
- 💰 **Price range** patterns
- 🚚 **Online delivery** availability and impact
- 🏢 **Restaurant chain** performance

The goal is to provide data-driven insights that can help restaurant owners, food delivery platforms, and consumers make informed decisions.

---

## 📊 Dataset Description

The dataset comprises **9,551 restaurants** with **21 comprehensive attributes**:

| Feature | Description | Type |
|---------|-------------|------|
| 🆔 Restaurant ID | Unique identifier for each restaurant | Numeric |
| 🏪 Restaurant Name | Name of the restaurant | Text |
| 🌍 Country Code | Numerical code for country | Numeric |
| 🏙️ City | City where restaurant is located | Text |
| 📍 Address | Physical address | Text |
| 📌 Locality | Neighborhood details | Text |
| 🗺️ Longitude & Latitude | Geographical coordinates | Numeric |
| 🍽️ Cuisines | Types of cuisines offered | Text |
| 💵 Average Cost for Two | Average cost for two people | Numeric |
| 💱 Currency | Currency code | Text |
| 📅 Has Table Booking | Table booking availability | Boolean |
| 🚚 Has Online Delivery | Online delivery service availability | Boolean |
| 🔄 Is Delivering Now | Currently delivering status | Boolean |
| 📱 Switch to Order Menu | Online order menu availability | Boolean |
| 💰 Price Range | Price category (1-4) | Numeric |
| ⭐ Aggregate Rating | Average rating score | Numeric |
| 🎨 Rating Color & Text | Visual indicator of rating quality | Text |
| 👥 Votes | Number of votes | Numeric |

**Dataset Statistics:**
- **Total Restaurants:** 9,551
- **Unique Cuisine Combinations:** 1,825
- **Cities Covered:** Multiple international locations
- **Price Ranges:** 4 categories (Budget to Premium)

---

## 🔍 Key Insights

### 🍜 Cuisine Analysis

**Top 3 Most Popular Cuisines:**
1. **North Indian** - 9.8% of all restaurants
2. **North Indian, Chinese** - 5.35%
3. **Chinese** - 3.7%

**Key Findings:**
- 📊 **1,825 unique cuisine combinations** showcase incredible diversity
- ⭐ Premium cuisines like *World Cuisine* and *Vegetarian* tend to have **higher average ratings**
- 🌏 Multi-cuisine restaurants (offering 2+ cuisines) are increasingly popular

### 🏙️ City and Ratings

**Geographic Distribution:**
- 🥇 **New Delhi** has the highest number of restaurants
- ⭐ **Inner City** boasts the highest average restaurant rating
- 📈 Significant variation in average ratings across different cities

**Insights:**
- Metropolitan areas show higher restaurant density
- Smaller cities often have higher average ratings (less competition, more focused quality)

### 💰 Pricing Trends

**Price Range Distribution:**

| Price Range | Percentage | Description |
|-------------|-----------|-------------|
| 💵 Range 1 | 46.53% | Budget-friendly |
| 💵💵 Range 2 | 32.59% | Moderate |
| 💵💵💵 Range 3 | 14.74% | Premium |
| 💵💵💵💵 Range 4 | 6.14% | Luxury |

**Key Observations:**
- Nearly **half** of all restaurants fall into the budget category
- Only **6.14%** are luxury establishments
- Price range correlates with location and cuisine type

### 🚚 Online Delivery Impact

**Delivery Statistics:**
- 📦 **25.66%** of restaurants offer online delivery
- ⭐ Restaurants **with** online delivery: **3.25** average rating
- ⭐ Restaurants **without** online delivery: **2.46** average rating

**Analysis:**
- Online delivery availability shows a **+0.79 rating boost**
- Restaurants investing in delivery infrastructure tend to have better overall service
- Growing trend toward digital ordering platforms

### ⭐ Ratings & Popularity

**Engagement Metrics:**
- 📊 **Average votes per restaurant:** ~157
- 📈 **Positive correlation:** Higher-rated restaurants receive more votes
- 🎯 Popular restaurants (500+ votes) maintain ratings above 4.0

**Insights:**
- Customer engagement is a strong indicator of quality
- Highly-rated restaurants benefit from positive feedback loops

### 🏢 Restaurant Chains

**Major Chains Analyzed:**
- ☕ Cafe Coffee Day
- 🍕 Domino's Pizza
- 🥪 Subway
- 🍗 Green Chick Chop
- 🍔 McDonald's

**Findings:**
- Chain restaurants show **variation in ratings** across locations
- Consistency in service quality varies by brand
- Local adaptations impact customer satisfaction

---

## 📈 Visualizations

The analysis includes rich, interactive visualizations:

- 📊 **Histogram:** Price range distribution across all restaurants
- 📉 **Bar Plots:** City-wise average ratings comparison
- 🗺️ **Scatter Plots:** Geographic distribution using longitude/latitude
- 🌍 **Interactive Maps:** Plotly-powered geo-visualization of restaurant locations
- 📈 **Correlation Heatmaps:** Relationship between ratings, votes, and delivery
- 🥧 **Pie Charts:** Cuisine and price range distributions

All visualizations are available in the Jupyter notebook for interactive exploration.

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| **Language** | ![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python) |
| **Data Analysis** | `pandas`, `numpy` |
| **Visualization** | `matplotlib`, `seaborn`, `plotly.express` |
| **Environment** | Jupyter Notebook |
| **Data Format** | CSV |

---

## 💻 Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Setup Instructions

1. **Clone the repository:**
```bash
git clone https://github.com/yourusername/Restaurant-Analysis.git
cd Restaurant-Analysis
```

2. **Install required packages:**
```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### Running the Analysis

1. **Launch Jupyter Notebook:**
```bash
jupyter notebook
```

2. **Open the analysis notebook:**
   - Navigate to `Restaurant Analysis.ipynb`
   - Run cells sequentially to reproduce the analysis

3. **Explore the data:**
   - The dataset is loaded from `Restaurant Dataset.csv`
   - Modify code cells to perform custom analyses
   - Generate new visualizations based on your interests
---

## 📁 Project Structure

```
Restaurant-Analysis/
├── Restaurant Analysis.ipynb    # Main Jupyter notebook with complete EDA
└── Restaurant Dataset.csv        # Raw dataset (9,551 restaurants)
```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch:** `git checkout -b feature/AmazingFeature`
3. **Commit your changes:** `git commit -m 'Add some AmazingFeature'`
4. **Push to the branch:** `git push origin feature/AmazingFeature`
5. **Open a Pull Request**

### Contribution Ideas:
- 🐛 Bug fixes and error handling
- 📊 Additional visualizations
- 📝 Documentation improvements
- 🧪 Unit tests for data processing functions
- 🎨 Enhanced visual design for plots

---

## 📬 Contact

**Ch Ayushman Patro**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/ch-ayushman-patro)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?logo=github)](https://github.com/Ch-Ayushman-Patro)

For questions, suggestions or collaboration opportunities, feel free to reach out!


