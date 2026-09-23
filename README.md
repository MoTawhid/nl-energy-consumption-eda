# 🇳🇱 Netherlands Energy Consumption Analysis 2024

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Data Source](https://img.shields.io/badge/Data-ENTSO--E-green)](https://transparency.entsoe.eu/)

## 📋 Overview

An exploratory data analysis (EDA) of the **Netherlands' 2024 hourly electricity load data** sourced from the ENTSO-E Transparency Platform. This project uncovers consumption patterns across seasons, weeks, and hours to provide actionable insights for grid optimization and energy forecasting.

**Author:** Mohamed Tawhid  
**Role:** Energy Analyst | Power System Specialist

---

## 🎯 Objectives

- Analyze the Netherlands' 2024 hourly load data (8,784 hours)
- Identify seasonal, weekly, and daily consumption patterns
- Provide actionable strategies for grid optimization
- Establish foundation features for predictive modeling

---

## 📊 Key Findings

### 1. Seasonality Drives Demand
- **Winter months (Jan & Dec):** Peak average loads exceeding **14,500 MW**
- **Summer months (June/July):** Dip to approximately **11,900 MW**
- Clear "U-shaped" consumption curve across the year

### 2. The Daily "Duck Curve"
- **Overnight minimum:** 4-5 AM (~10,500 MW)
- **Morning rise:** Sharp increase from 6 AM
- **Evening peak:** Highest demand between **6-8 PM**

### 3. Weekday vs. Weekend
- Consistent drop in weekend consumption
- Highlights massive commercial and industrial impact

### 4. Load Duration Curve
- **Top 10% of hours:** Load > 16,000 MW
- **Bottom 10% of hours:** Load < 10,750 MW

---

## 🛠️ Technologies Used

| Tool | Purpose |
|------|---------|
| **Python 3.8+** | Core programming language |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical computations |
| **Matplotlib** | Static visualizations |
| **Seaborn** | Statistical data visualization |
| **Jupyter Notebook** | Interactive analysis environment |

---

## 📁 Repository Structure
