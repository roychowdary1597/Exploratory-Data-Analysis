# 🚗 UK Electric Vehicle (EV) Dataset Analysis

This project presents a comprehensive **exploratory data analysis (EDA)** of electric vehicles (EVs) available in the UK market. The data was **scraped from [ev-database.org](https://ev-database.org/uk/)** and includes vehicle specifications, efficiency metrics, and pricing.

---

## 📌 Problem Statement

> **To analyze the UK electric vehicle market based on range, price, efficiency, and specifications, and identify EVs that offer the best value for money.**

---

## 📦 Dataset Features

| Column                    | Description                                   |
|---------------------------|-----------------------------------------------|
| `Brand`                   | Manufacturer of the vehicle                   |
| `Model`                   | Specific EV model name                        |
| `Availability`            | Region-wise launch/availability info          |
| `Availability_Status`     | Whether the model is current/upcoming/archive |
| `Range(in_mile)`          | Driving range on a single charge              |
| `Efficiency(Wh/mile)`     | Energy used per mile                          |
| `Weight_in_Kg`            | Vehicle weight                                |
| `t_0_60_mph`              | Acceleration from 0 to 60 mph (seconds)       |
| `Battery_Capacity(kWh)`   | Usable battery capacity                       |
| `Seating_Capacity`        | Number of seats                               |
| `Boot Space(in_Litres)`   | Luggage storage capacity                      |
| `Model Price(in_£)`       | Retail price in GBP                           |
| `Price_Per_Range(in_£)`   | Price per mile of range                       |

---


## 🛠️ Tools & Libraries Used

- **Python**
- **Pandas** – data cleaning & transformation
- **BeautifulSoup** – web scraping
- **Matplotlib / Seaborn** – visualizations
- **Jupyter Notebook**

---

## 📊 Exploratory Data Analysis (EDA)

### 🔋 Battery vs Range
Visualizes how larger battery capacities typically result in longer driving ranges.

### 💰 Price vs Range
Analyzes pricing trends relative to how far a car can go per charge.

### ⚡ Weight vs Efficiency
Reveals how heavier EVs tend to consume more energy per mile.

### 🚀 Acceleration vs Price
Shows that faster EVs usually come with a higher price tag.

### 👥 Seating Capacity Count
Distribution of how many seats EVs typically have (e.g., 2-seater, 5-seater).

### 🏷️ Top Brands by EV Model Count
Highlights which manufacturers offer the most EV options in the UK.

---

## 📉 Sample Visualizations

> 📌 _Visualizations are available in the notebook `ev_analysis.ipynb`_

- Scatter plot: `Range vs Price`
- Histogram: `Price_Per_Range`
- Count plot: `Seating_Capacity`
- Boxplot: `Efficiency(Wh/mile)` across Brands
- Bar chart: Top 10 EV brands by model count

---

## 💡 Key Insights

- **Tesla, Audi, and BMW** dominate the premium segment, while **MG, Nissan, and Hyundai** offer excellent value per mile.
- Vehicles with **higher weight** tend to be **less energy efficient**.
- **Most EVs** fall in the **200–300 mile range** bracket.
- **Acceleration (0–60 mph)** strongly correlates with price.
- EVs with **better efficiency** are not always the most expensive.

---

