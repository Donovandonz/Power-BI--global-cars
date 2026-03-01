# Power-BI--global-cars
🚗 Global Cars Dashboard - Excel + Power BI Project

Dataset used

-<a href="https://github.com/Donovandonz/Power-BI--global-cars/blob/main/global_cars_dataset_synthetic.csv">RAW.global-cars</a>

---

## 📌 Project Overview

This **Cars Catalog Dashboard** provides a comprehensive analysis of a car inventory dataset with **300 vehicles** across multiple brands, body types, fuel types, and manufacturing countries. Built using **Excel for data processing** and **Power BI for interactive visualization**, this dashboard enables stakeholders to explore car specifications, pricing trends, and performance metrics through dynamic visualizations and filters.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **📗 Excel** | Data cleaning, transformation, and initial exploration |
| **📊 Power BI** | Interactive dashboard creation, DAX calculations, and visualization |

---

### 🎯 Dashboard Objectives
- Analyze average engine capacity, horsepower, and fuel efficiency across brands
- Track pricing trends and inventory distribution
- Understand regional manufacturing patterns
- Explore relationships between fuel type, transmission, and body style
- Provide interactive filters for real-time data exploration

---

## 📂 Dataset Description

The dataset contains car catalog information with the following fields:

| Column | Description |
|--------|-------------|
| `Car_ID` | Unique identifier for each car |
| `Brand` | Car manufacturer (Mercedes, Honda, Toyota, Nissan, etc.) |
| `Manufacture_Year` | Year of manufacture (2005, 2010, 2015, 2020, 2025) |
| `Body_Type` | Sedan, SUV, Coupe, Hatchback, Pickup |
| `Fuel_Type` | Petrol, Diesel, Hybrid, Electric |
| `Transmission` | Automatic / Manual |
| `Engine_CC` | Engine displacement (cubic centimeters) |
| `Horsepower` | Engine power output |
| `Mileage_km_per_l` | Kilometers per liter (KM/L) - fuel efficiency |
| `Price_USD` | Car price (in thousands of USD) |
| `Manufacturing_Country` | Country of origin (Germany, Japan, USA, etc.) |

---

## 📊 Key Performance Indicators

| Metric | Value |
|--------|-------|
| 🚗 **Total Cars** | **300** |
| 💰 **Average Price** | **$60.85K** |
| ⚡ **Average Horsepower** | **328.35 HP** |
| ⛽ **Avg Fuel Efficiency** | **19.72 KM/L** |
| 🔧 **Avg Engine CC** | Varies by Brand |

---

## 🏆 Brand Performance Analysis

### Average Engine CC by Brand

| Rank | Brand | Avg Engine CC | Performance Grade |
|:----:|-------|:-------------:|-------------------|
| **1** 🥇 | **Mercedes** | **Highest** | 🟪 **PREMIUM** |
| **2** 🥈 | **Toyota** | **High** | 🟥 STRONG |
| **3** 🥉 | **Nissan** | **High** | 🟥 STRONG |
| 4 | Hyundai | Moderate | 🟨 AVERAGE |
| 5 | Audi | Moderate | 🟨 AVERAGE |
| 6 | Ford | Moderate | 🟨 AVERAGE |
| 7 | Kia | Low | 🟧 BELOW AVG |
| 8 | BMW | Low | 🟧 BELOW AVG |
| 9 | Tesla | **Electric** | 🟪 **EV LEADER** |


**📌 Brand Insights:**
- **Mercedes leads** in engine displacement - premium German engineering
- **Toyota and Nissan** follow closely - reliable Japanese performance
- **Tesla** stands apart with **electric powertrain** - different category
- **Kia and BMW** at lower end - focus on efficiency over displacement

---

## 🌍 Regional Manufacturing Insights

### Count of Brand by Manufacturing Country

| Rank | Country | Brands | Market Share | Grade |
|:----:|---------|:------:|:------------:|-------|
| **1** 🥇 | **Germany** | Mercedes, BMW, Audi | 3 brands | 🟪 **PREMIUM HUB** |
| **2** 🥈 | **Japan** | Toyota, Honda, Nissan | 3 brands | 🟪 **VOLUME LEADER** |
| **3** 🥉 | **USA** | Ford, Tesla | 2 brands | 🟥 STRONG |
| 4 | **South Korea** | Hyundai, Kia | 2 brands | 🟥 GROWING |
| 5 | **China** | 1 brand | 1 brand | 🟨 EMERGING |
| 6 | **UK** | 1 brand | 1 brand | 🟨 NICHE |

---

**📌 Regional Insights:**
- **Germany and Japan** tied as **top manufacturing countries** with 3 brands each
- **Germany** specializes in **premium/luxury** vehicles
- **Japan** focuses on **reliability and volume**
- **USA** represented by **Ford (traditional) and Tesla (innovator)**
- **South Korea** emerging as strong contender with **Hyundai & Kia**

---

## 🚘 Body Type Distribution

| Rank | Body Type | Count | Popularity Grade |
|:----:|-----------|:-----:|------------------|
| **1** 🥇 | **SUV** | **105** | 🟪 **MOST POPULAR** |
| **2** 🥈 | **Sedan** | **84** | 🟥 STRONG |
| **3** 🥉 | **Coupe** | **54** | 🟨 AVERAGE |
| 4 | **Hatchback** | **36** | 🟨 AVERAGE |
| 5 | **Pickup** | **21** | 🟧 NICHE |


**📌 Body Type Insights:**
- **SUV dominates** the catalog (35%) - reflects global market trend
- **Sedan remains strong** (28%) - traditional preference continues
- **Pickup trucks** are niche (7%) - specialized market segment
- **Hatchback** appeals to **economy-conscious** buyers (12%)

--- 

## ⛽ Fuel Type & Transmission Analysis

### Count of Cars by Fuel Type and Transmission

| Fuel Type | Automatic | Manual | Total | % of Fleet | Grade |
|-----------|:---------:|:------:|:-----:|:----------:|-------|
| **Hybrid** | 32 | 45 | **77** | **25.7%** | 🟪 **TOP** |
| **Petrol** | 40 | 37 | **77** | **25.7%** | 🟪 **TOP** |
| **Diesel** | 40 | 35 | **75** | **25.0%** | 🟥 HIGH |
| **Electric** | 33 | 38 | **71** | **23.6%** | 🟥 HIGH |
| **TOTAL** | **145** | **155** | **300** | **100%** | |

**📌 Fuel & Transmission Insights:**
- **Hybrid and Petrol** tie as most popular fuel types with **77 cars each (25.7%)**
- **Diesel** follows closely with **75 cars (25.0%)**
- **Electric** represents **71 cars (23.6%)** - strong EV presence
- **Manual transmission leads slightly** with **51.7%** (155 cars)
- **Automatic** accounts for **48.3%** (145 cars) - nearly balanced
- **Hybrid and Electric** both show **manual preference** (58% and 54%)
- **Petrol and Diesel** are **balanced** between auto and manual

---

## 📅 Year-wise Analysis

### Manufacture Year Distribution

| Year | Count | Trend |
|:----:|:-----:|-------|
| **2025** | 15 | 🟪 **NEWEST** |
| **2023** | 20 | 🟥 STRONG |
| **2022** | 10 | 🟥 STRONG |
| **2021** | 13 | 🟥 STRONG |
| **2020** | 27 | 🟨 AVERAGE |
| **2019** | 15 | 🟧 DECLINING |
| **2018** | 12 | 🟥 OLDEST |
| **2017** | 14 | 🟥 OLDEST |
| **2016** | 13 | 🟥 OLDEST |
| **2015** | 16 | 🟥 OLDEST |
| **2014** | 12 | 🟥 OLDEST |
| **2013** | 17 | 🟥 OLDEST |
| **2012** | 15 | 🟥 OLDEST |
| **2011** | 7 | 🟥 OLDEST |
| **2010** | 19 | 🟥 OLDEST |
| **2009** | 15 | 🟥 OLDEST |
| **2008** | 9 | 🟥 OLDEST |
| **2007** | 18 | 🟥 OLDEST |
| **2006** | 15 | 🟥 OLDEST |
| **2005** | 11 | 🟥 OLDEST |

### 📈 Year-wise Trends

| Period | Total Cars | % of Fleet | Trend |
|--------|:----------:|:----------:|-------|
| **2020-2025** | 100 | **33.3%** | 🟪 **NEWEST STOCK** |
| **2010-2019** | 140 | **46.7%** | 🟨 MID-RANGE |
| **2005-2009** | 60 | **20.0%** | 🟧 OLDER STOCK |


**📌 Year Distribution Insights:**
- **2020 peak** with 27 cars - strongest production year
- **Balanced inventory** across two decades
- **2023 strong** with 20 cars - recent growth
- **2011 lowest** with only 7 cars
- **33% of inventory** from 2020-2025 - fresh stock
- **47% from 2010-2019** - core mid-range inventory
- **20% pre-2010** - classic/older segment

---

### ⚡ Horsepower by Brand

| Rank | Brand | Avg Horsepower | Performance Grade |
|:----:|-------|:--------------:|-------------------|
| **1** 🥇 | **Ford** | **361 HP** | 🟪 **HIGHEST** |
| **2** 🥈 | **Toyota** | **366 HP** | 🟪 HIGHEST |
| **3** 🥉 | **KIA** | **353 HP** | 🟥 VERY HIGH |
| 4 | **Mercedes** | **337 HP** | 🟥 VERY HIGH |
| 5 | **Audi** | **337 HP** | 🟥 VERY HIGH |
| 6 | **Nissan** | **309 HP** | 🟨 AVERAGE |
| 7 | **Honda** | **269 HP** | 🟧 BELOW AVG |
| 8 | **BMW** | **274 HP** | 🟧 BELOW AVG |
| 9 | **Hyundai** | **264 HP** | 🟧 BELOW AVG |
| 10 | **Tesla** | **376 HP** | 🟪 **ELECTRIC** |


### 📊 Horsepower Insights

| Tier | HP Range | Brands | Count |
|------|----------|--------|-------|
| 🟪 **ELITE** | 360+ HP | Toyota, Ford, Tesla | 3 |
| 🟥 **HIGH** | 330-359 HP | KIA, Mercedes, Audi | 3 |
| 🟨 **AVERAGE** | 300-329 HP | Nissan | 1 |
| 🟧 **BELOW AVG** | <300 HP | BMW, Honda, Hyundai | 3 |

**📌 Horsepower Key Takeaways:**
- **Toyota leads traditional brands** with 366 HP - surprising performance from reliability-focused brand
- **Ford** close second at 361 HP - American muscle
- **KIA** outperforms luxury brands at 353 HP - Korean engineering surprise
- **Tesla at 376 HP** but electric - different category
- **Mercedes and Audi** tied at 337 HP - German precision
- **Hyundai lowest** at 264 HP - economy focus over performance
- **BMW underperforms** at 274 HP - below expected for luxury brand

---

### 💰 Price Analysis by Brand

| Rank | Brand | Avg Price (USD) | Segment | Performance Grade |
|:----:|-------|:---------------:|---------|-------------------|
| **1** 🥇 | **Mercedes** | **$69,850** | 🟪 **Luxury** | 🟪 **PREMIUM** |
| **2** 🥈 | **Toyota** | **$67,980** | 🟪 Premium | 🟪 VERY HIGH |
| **3** 🥉 | **KIA** | **$62,640** | 🟪 Premium | 🟥 HIGH |
| 4 | **Ford** | **$60,400** | 🟥 Mainstream | 🟥 HIGH |
| 5 | **Nissan** | **$58,650** | 🟥 Mainstream | 🟨 AVERAGE |
| 6 | **Audi** | **$58,060** | 🟪 Premium | 🟨 AVERAGE |
| 7 | **BMW** | **$57,950** | 🟪 Premium | 🟨 AVERAGE |
| 8 | **Hyundai** | **$57,520** | 🟥 Mainstream | 🟨 AVERAGE |
| 9 | **Tesla** | **$59,750** | 🟪 Premium | 🟨 AVERAGE |
| 10 | **Honda** | **$53,240** | 🟥 Mainstream | 🟧 **BEST VALUE** |


### 📈 Price vs Brand Perception

| Brand | Price | Segment | Value Proposition |
|-------|:-----:|---------|-------------------|
| **Mercedes** | $69,850 | 🟪 Luxury | Commands premium pricing |
| **Toyota** | $67,980 | 🟪 Premium | Defying expectations - near-luxury pricing |
| **KIA** | $62,640 | 🟪 Premium | Successfully moved upmarket |
| **Honda** | $53,240 | 🟥 Mainstream | **Best value** - affordable quality |
| **BMW** | $57,950 | 🟪 Premium | Underpriced vs competitors? |
| **Tesla** | $59,750 | 🟪 Premium | Competitive EV pricing |

---

### 💡 Price Insights

- **Mercedes commands highest price** at $69,850 - true luxury positioning
- **Toyota surprises** at #2 ($67,980) - premium pricing for reliability reputation
- **KIA outperforms** Ford, Nissan, Audi in pricing - brand elevation success
- **Honda offers best value** at $53,240 - most affordable among major brands
- **BMW priced below** Audi and Nissan - potential bargain in premium segment
- **Price gap**: Mercedes to Honda = **$16,610 difference**
- **Average premium tier price**: ~$59,500

---

### 🔍 Price vs Performance Correlation

| Brand | Price | AVG HP | Value Ratio (HP per $1K) |
|-------|:-----:|:--:|:------------------------:|
| **Ford** | $60,400 | 361 HP | 5.98 HP/$1K |
| **Toyota** | $67,980 | 366 HP | 5.38 HP/$1K |
| **KIA** | $62,640 | 353 HP | 5.64 HP/$1K |
| **Nissan** | $58,650 | 309 HP | 5.27 HP/$1K |
| **Honda** | $53,240 | 269 HP | **5.05 HP/$1K** |

**Best Performance Value:** Ford (5.98 HP per $1,000)  
**Best Overall Value:** Honda (lowest price, respectable performance)

---

### ⛽ Fuel Efficiency by Brand (KM/L)

| Rank | Brand | Avg Fuel Efficiency (KM/L) | Efficiency Grade |
|:----:|-------|:--------------------------:|------------------|
| **1** 🥇 | **Tesla** | **N/A (Electric)** | 🟪 **ZERO EMISSIONS** |
| **2** 🥈 | **Hyundai** | **20.97 KM/L** | 🟪 **MOST EFFICIENT** |
| **3** 🥉 | **Honda** | **20.85 KM/L** | 🟪 VERY HIGH |
| 4 | **Mercedes** | **20.39 KM/L** | 🟥 HIGH |
| 5 | **Audi** | **20.08 KM/L** | 🟥 HIGH |
| 6 | **Nissan** | **19.95 KM/L** | 🟨 AVERAGE |
| 7 | **Toyota** | **19.94 KM/L** | 🟨 AVERAGE |
| 8 | **Ford** | **19.89 KM/L** | 🟨 AVERAGE |
| 9 | **KIA** | **18.77 KM/L** | 🟧 BELOW AVG |
| 10 | **BMW** | **18.71 KM/L** | 🟧 BELOW AVG |


### 📊 Fuel Efficiency Tier Analysis

| Tier | KM/L Range | Brands | Count |
|------|------------|--------|-------|
| 🟪 **EXCELLENT** | 20.5+ KM/L | Hyundai, Honda | 2 |
| 🟥 **HIGH** | 20.0-20.5 KM/L | Mercedes, Audi | 2 |
| 🟨 **AVERAGE** | 19.5-20.0 KM/L | Nissan, Toyota, Ford | 3 |
| 🟧 **BELOW AVG** | <19.0 KM/L | KIA, BMW | 2 |
| 🟪 **ELECTRIC** | N/A | Tesla | 1 |


### 📈 Efficiency vs Performance Trade-off

| Brand | Fuel Efficiency | Horsepower | Trade-off |
|-------|:---------------:|:----------:|-----------|
| **Hyundai** | 20.97 KM/L (🥇) | 264 HP (😟) | 🟢 **Efficiency King** |
| **Honda** | 20.85 KM/L (🥈) | 269 HP (😟) | 🟢 **Efficiency Focus** |
| **Mercedes** | 20.39 KM/L (👍) | 337 HP (👍) | ⭐ **BEST BALANCE** |
| **Toyota** | 19.94 KM/L (😐) | 366 HP (🥇) | 🟡 **Performance Biased** |
| **BMW** | 18.71 KM/L (😟) | 274 HP (😐) | 🔴 **Low Efficiency** |


### 🔍 Key Fuel Efficiency Insights

- **Hyundai surprises** as the **most efficient** traditional brand at **20.97 KM/L**
- **Honda** close second at **20.85 KM/L** - consistent efficiency leader
- **Mercedes defies expectations** - luxury brand achieves **20.39 KM/L** (4th place)
- **Audi** also impresses at **20.08 KM/L** - German efficiency improving
- **Toyota** mid-pack at **19.94 KM/L** despite highest horsepower (366 HP)
- **BMW** has **lowest efficiency** at **18.71 KM/L** - performance priority
- **KIA** also struggles at **18.77 KM/L** - room for improvement

---

### 💡 Surprising Findings

| Finding | Insight |
|---------|---------|
| **Hyundai > Honda** | Korean brand edges out Japanese efficiency leader |
| **Mercedes > Toyota** | Luxury German brand more efficient than reliability king |
| **Audi > Nissan** | Premium brand outperforms mainstream Japanese |
| **BMW Last Place** | Performance focus comes at efficiency cost |
| **Tesla Effect** | Electric eliminates efficiency concerns |

---

### 🏆 Efficiency Champions

| Category | Brand | KM/L | Grade |
|----------|-------|:----:|-------|
| **Overall Champion** | Hyundai | 20.97 | 🟪 **GOLD** |
| **Runner Up** | Honda | 20.85 | 🟪 **SILVER** |
| **Luxury Leader** | Mercedes | 20.39 | 🟥 **BRONZE** |
| **Most Improved** | Audi | 20.08 | 🟥 **HONORABLE** |
| **Needs Improvement** | BMW | 18.71 | 🟧 **WATCH** |


---

## 🚗 Dashboard Overview

-<a href="https://github.com/Donovandonz/Power-BI--global-cars/blob/main/Cars-dashboard.png">Cars-dashboard</a>

<img width="1312" height="737" alt="Cars-dashboard" src="https://github.com/user-attachments/assets/79cb53f4-f8ad-4704-a540-429aeec33974" />




