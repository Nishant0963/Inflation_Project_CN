# India CPI Inflation Analysis — Excel Dashboard

## 📌 Project Overview

This project analyzes the **Consumer Price Index (CPI) in India** using **Microsoft Excel**. The objective is to understand inflation trends, category-wise price movements, the impact of COVID-19, food price changes, and the relationship between global oil prices and domestic inflation.

The complete project was developed using **Excel only**, including data cleaning, calculations, categorization, PivotTables, charts, correlation analysis, and dashboard creation.

---

## 🎯 Business Objectives

The analysis focuses on five key questions:

1. **Category Contribution**
    - Identify how major CPI categories contribute to the overall CPI.
    - Determine which category has the highest impact.
2. **Year-on-Year CPI Trend**
    - Analyze annual CPI/inflation trends from 2017 onward.
    - Compare rural and urban inflation.
    - Identify years with significant inflation spikes and investigate possible reasons.
3. **Food Price Trend**
    - Analyze monthly food-price movements for the 12 months ending May 2023.
    - Identify the highest and lowest monthly changes.
    - Determine important food sub-categories affecting food inflation.
4. **COVID-19 Impact**
    - Analyze changes in inflation before and after March 2020.
    - Focus on food, healthcare, and essential services.
5. **Global Economic Events**
    - Examine the relationship between global oil-price movements and Indian inflation.
    - Analyze categories such as energy and transportation.

---

## 🛠️ Tools Used

- **Microsoft Excel**
- Excel Tables
- Data Cleaning
- Formulas
- PivotTables
- Pivot Charts
- Conditional Formatting
- Correlation Analysis
- Dashboard Design

---

## 📊 Dataset

The dataset contains Indian CPI information across different time periods and categories.

Major CPI categories/components used in the analysis include:

- Food
- Energy / Fuel & Light
- Clothing
- Housing
- Health
- Transport & Communication
- Education
- Personal Care & Effects
- Recreation & Amusement
- Household Goods & Services
- General Index

Food was further analyzed using sub-categories such as:

- Cereals and Products
- Meat and Fish
- Egg
- Milk and Products
- Oils and Fats
- Fruits
- Vegetables
- Pulses and Products
- Sugar and Confectionery
- Spices
- Non-Alcoholic Beverages
- Prepared Meals, Snacks and Sweets

---

# 🔄 Project Workflow

```
Raw CPI Data
     ↓
Data Cleaning
     ↓
Data Validation
     ↓
Category / Bucket Creation
     ↓
CPI Calculations
     ↓
PivotTables
     ↓
Trend & Contribution Analysis
     ↓
Correlation Analysis
     ↓
Excel Dashboard
     ↓
Business Insights
```

---

# 🧹 Data Preparation & Cleaning

The raw CPI data was prepared in Excel before analysis.

Key activities included:

- Removing duplicate records
- Handling missing/null values
- Checking incorrect or inconsistent values
- Standardizing date/month information
- Organizing CPI categories
- Creating major CPI buckets
- Separating rural and urban data where required
- Validating calculated values before dashboard creation

---

# 📦 CPI Category Buckets

To simplify category-level analysis, individual CPI components were grouped into major buckets.

```
CPI
│
├── Food
│
├── Energy
│
├── Clothing
│
├── Housing
│
├── Health & Education
│
├── Transport
│
├── Personal Care
│
└── Goods & Services
```

These buckets were used for contribution, trend, and comparative analysis.

---

# 📈 Analysis 1 — Category Contribution

The latest month's CPI data was used to understand the contribution/relative impact of major categories.

The analysis focused on identifying:

- Category-level contribution
- Highest-impact category
- Relative importance of Food, Energy, Transport, Housing, etc.

### Key Insight

**“Pan, tobacco and intoxicants” is the highest component of India's CPI basket and therefore plays a major role in understanding consumer inflation.**

> Note: CPI index values should not be summed across months. Latest-month values/weights should be used appropriately when calculating contribution.
> 

---

# 📅 Analysis 2 — Year-on-Year CPI Trend

Annual CPI/inflation trends were analyzed from **2017 onward**, with comparisons between rural and urban areas.

### Key observations

- Inflation varied across the years.
- COVID-19 caused major economic and supply disruptions around 2020.
- Inflationary pressure increased during the post-pandemic recovery.
- Global commodity and energy-price pressures became significant during 2021–2022.
- Food and fuel remained important contributors to inflation.

### Possible reasons for inflation spikes

- Global commodity prices
- Crude oil price movements
- Supply-chain disruptions
- Russia–Ukraine war
- Food-price increases
- Post-COVID demand recovery
- Transportation and logistics costs

---

# 🍎 Analysis 3 — Food Price Trend

The project analyzed the **12 months ending May 2023** to understand monthly food-price movements.

### Food Bucket Monthly Movement

| Month | MoM Change |
| --- | --- |
| June | 0.00 |
| July | 0.20 |
| August | 0.07 |
| September | 0.51 |
| October | 0.69 |
| November | -0.02 |
| December | -0.55 |
| January | 0.43 |
| February | -0.62 |
| March | 0.00 |
| April | 0.48 |
| May | 0.75 |

### Key Finding

- **Highest monthly increase:** May 2023 — **0.70%**
- **Lowest monthly movement:** February 2023 —  -**0.62%**

The food category showed a fluctuating pattern rather than a continuously increasing trend.

Subcategories Affecting Food Inflation :

| Categories | JUNE(2022) | MAY(2023) | Absolute Change |
| --- | --- | --- | --- |
| Cereals and products | 155.4 | 173.9 | 18.4 |
| Meat and fish | 220.0 | 215.1 | -4.9 |
| Egg | 171.1 | 173.6 | 2.6 |
| Milk and products | 165.9 | 179.5 | 13.6 |
| Oils and fats | 199.2 | 169.2 | -30.0 |
| Fruits | 169.9 | 172.3 | 2.5 |
| Vegetables | 187.0 | 164.9 | -22.1 |
| Pulses and products | 164.2 | 175.8 | 11.6 |
| Confectionery | 120.1 | 122.9 | 2.8 |
| Spices | 186.5 | 217.0 | 30.5 |
| Non-alcoholic beverages | 167.1 | 172.7 | 5.6 |
| Prepared meals, snacks, sweets etc. | 184.0 | 194.3 | 10.3 |

Spices had the greatest impact in terms of absolute change.

---

# 🦠 Analysis 4 — COVID-19 Impact

**March 2020** was used as the reference point for the onset of COVID-19.

The analysis compared inflation patterns before and after March 2020.

!image.png

### Areas of Focus

- Food
- Healthcare
- Fuel and light
- Household goods and services

### Key observations

COVID-19 affected inflation through:

- Nationwide lockdowns
- Supply-chain disruptions
- Transportation restrictions
- Changes in consumer demand
- Reduced economic activity
- Increased healthcare requirements
- Disruptions in the availability and distribution of essential goods

### Conclusion

COVID-19 created a significant disruption in the normal inflation pattern, with different CPI categories responding differently to supply and demand changes.

---

# 🛢️ Analysis 5 — Global Oil Prices & Inflation

The project examined the relationship between global oil-price movements and Indian inflation during **2021–2023**.

### Economic Relationship

```
Global Oil Prices ↑
        ↓
Fuel Costs ↑
        ↓
Transportation Costs ↑
        ↓
Distribution & Logistics Costs ↑
        ↓
Cost of Goods & Services ↑
        ↓
Inflationary Pressure ↑
```

### Correlation Analysis

Correlation was used to understand the strength and direction of relationships between selected CPI categories.

| Category | Correlation |
| --- | --- |
| Food | -0.005 |
| Goods & Services | -0.016 |
| Energy | **0.169** |
| Clothing | 0.157 |
| Housing | 0.067 |

### Key Finding

Energy showed the strongest positive correlation among the analysed categories, at approximately **0.169**.

However, this represents a **weak positive correlation** and does not establish causation.

Other factors can also influence inflation, including:

- Food prices
- Supply disruptions
- Exchange rates
- Domestic demand
- Government policies
- Global commodity prices

---

# 📊 Excel Dashboard

The final Excel dashboard presents the analysis through KPI cards and visualizations.

### Preview :

!image.png

### Visualizations

- Annual CPI/Inflation Trend
- Rural vs Urban Inflation
- Food Inflation — Last 12 Months
- Category Contribution
- COVID Pre vs Post Analysis
- Oil Price vs Inflation
- Category Correlation Analysis

---

# 💡 Key Project Insights

The overall analysis indicates that:

1. **“Pan, tobacco and intoxicants” is the highest component of consumer inflation** and has an important influence on India's CPI.
2. CPI inflation changed significantly during the **COVID-19 period** because of supply-chain and demand disruptions.
3. **2021–2022** experienced stronger inflationary pressure due to global commodity, energy, and supply-side factors.
4. Food prices showed **month-to-month fluctuations**, with May 2023 recording the highest monthly increase in the analysed 12-month period.
5. Energy showed a **positive but weak correlation** with the selected inflation measures.
6. Inflation is influenced by multiple economic factors, so correlation alone should not be interpreted as causation.

---

# 📁 Project Structure

```
India-CPI-Inflation-Analysis/
│
├── README.md
│
├── Dataset/
│   └── CPI_Data.xlsx
│
├── Analysis/
│   └── CPI_Analysis.xlsx
│
└── Dashboard/
    └── CPI_Inflation_Dashboard.xlsx
```

---

# 🧠 Skills Demonstrated

This project demonstrates practical Excel Data Analyst skills:

- Data Cleaning
- Data Validation
- Data Transformation
- Excel Formulas
- CPI Calculations
- Percentage Change / MoM Analysis
- YoY Analysis
- Category Analysis
- Contribution Analysis
- PivotTables
- Pivot Charts
- Correlation Analysis
- Dashboard Development
- Data Visualization
- Business Insight Generation

---

# 📝 Project Conclusion

This project demonstrates how **Microsoft Excel can be used to perform an end-to-end data analysis project** using real-world economic data.

The analysis transforms raw CPI data into meaningful insights about **inflation trends, category contributions, food prices, COVID-19 effects, and global economic influences**.

The final dashboard provides a concise view of India's inflation patterns and helps identify the major factors associated with changes in consumer prices.

---

## 👨‍💻 Author

**Nishant Loomba**

**Project Type:** Data Analytics

**Tool:** Microsoft Excel

**Domain:** Economics / Inflation / Consumer Price Index
