# Project 2 
## Title: Analysis of Electric Vehicle Charging Patterns for Sustainable Transportation in the United States

## 📌 Project Overview
This project analyzes **Electric Vehicle (EV) charging patterns** to understand user behavior, station utilization, and temporal trends. By leveraging data on charging durations, station types, and locations, the goal is to optimize **EV charging infrastructure** for sustainable transportation in the United States.

## 📊 Dataset
The dataset used for this analysis is sourced from [Kaggle](https://www.kaggle.com/datasets/valakhorasani/electric-vehicle-charging-patterns/data). It contains:
- **Charging station types** (Level 1, Level 2, DC Fast Chargers)
- **Charging session durations**
- **Charging station locations**
- **Energy consumption & cost details**
- **Temporal trends in charging behavior**

## 🎯 Objectives
1. Identify key **charging behavior patterns**.
2. Determine the most **frequently used charger types**.
3. Optimize **charging station placement**.
4. Analyze **charging cost variations** across different charger types.
5. Explore the relationship between **cost and energy consumption**.
6. Support the development of **a sustainable EV charging ecosystem**.

## 🔍 Problem Statement
Understanding **EV charging behavior** is crucial for optimizing charging infrastructure. The project seeks to answer:
- What are the key **patterns** in EV charging behavior?
- Which **charging station types** are most used?
- How can data help in identifying **optimal locations** for charging stations?
- What is the **distribution of charging costs** across charger types?
- What is the **relationship between charging cost and energy consumption**?

## 📈 Key Analyses & Results
### 1️⃣ Charging Duration Analysis
- **Most charging sessions last between 1-4 hours**, peaking at around 2 hours.
- Users prefer medium-duration charging rather than short or full charge cycles.
- **DC Fast Chargers** are beneficial for quick recharges, while **Level 2 chargers** suit long-duration charging.

### 2️⃣ Charger Type Utilization
- **Level 1: 34.8%**, **Level 2: 32.7%**, **DC Fast Chargers: 32.6%**.
- Home-based Level 1 chargers dominate, while **public Level 2 chargers** and **DC Fast Chargers** are nearly equal.
- Balanced infrastructure is required to accommodate diverse EV users.

### 3️⃣ Charging Station Demand by Location
- **Los Angeles, San Francisco, and Houston** have the highest demand.
- Locations with lower charging demand require investigation into **accessibility and availability of stations**.
- Urban centers need **more fast chargers** due to high usage rates.

### 4️⃣ Charging Cost Analysis
- **DC Fast Chargers have the highest costs**, while Level 1 remains the most affordable.
- Some extreme outliers in cost suggest **pricing inconsistencies** that need regulation.

### 5️⃣ Cost vs. Energy Consumption
- **Weak correlation (-0.02) between charging cost and energy consumed**.
- Pricing is more dependent on **flat rates and session-based pricing** rather than per kWh usage.
- Calls for **more transparent and fair pricing mechanisms**.

### 6️⃣ Correlation Analysis
- **Energy Consumed (kWh) vs. Charging Duration (r ≈ 0.85)**: Strong positive correlation.
- **Charging Cost vs. Power Output (r ≈ 0.10)**: Weak correlation.
- **No strong relationship between energy consumption and cost** suggests diverse pricing strategies.

## 🛠 Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Google Colab** for data processing & visualization
- **Jupyter Notebook** for exploratory data analysis

## 🏁 Conclusion
- EV charging patterns indicate **a need for diverse and well-distributed charging infrastructure**.
- **DC Fast Chargers** are essential for quick stops, while **Level 2 chargers** are best for workplaces and public areas.
- **High-demand areas require infrastructure expansion**, while **underutilized locations** need further analysis.
- **Transparent pricing mechanisms** should be implemented to align costs with energy consumption.

## 📚 References
- **[Electric Vehicle Charging Patterns Dataset - Kaggle](https://www.kaggle.com/datasets/valakhorasani/electric-vehicle-charging-patterns/data)**
- Hardman, S. et al. (2018). *Consumer preferences for EV charging infrastructure*. Transportation Research.
- Nicholas, M. & Hall, D. (2019). *EV Charging Infrastructure Analysis*. International Council on Clean Transportation.
