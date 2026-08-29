# 🚗 Car Dekho Automotive Market Trends & Valuation Analysis

An end-to-end Exploratory Data Analysis (EDA) and econometric case study evaluating **301 pre-owned vehicle transactions** from the Indian automotive secondary marketplace. This project investigates primary price drivers, brand-level depreciation curves, fuel & transmission distributions, and segment dynamics between two-wheelers and four-wheelers.

---

## 📌 Executive Summary
* **Domain:** Automotive Analytics & Secondary Market Valuation
* **Tech Stack:** Python 3 (Pandas, NumPy, Matplotlib, Seaborn), Jupyter Notebook
* **Dataset Scope:** 301 verified vehicle records across 9 commercial attributes
* **Manufacturing Timeline:** 2003 – 2018
* **Market Pricing Spectrum:** **₹0.10 Lakh to ₹35.00 Lakh** (Mean: ₹4.66 Lakh)
* **Fleet Segmentation:** 200 Four-Wheelers (Cars) | 101 Two-Wheelers (Bikes & Scooters)

---

## 🛠️ Data Engineering & Feature Processing
* **Integrity Audit:** Verified zero missing/null values across the entire dataset.
* **Depreciation Modeling:** Derived absolute depreciation (`Present_Price - Selling_Price`) and percentage value retention metrics per vehicle and manufacturer.
* **Categorical Mapping:** Segmented vehicles into Two-Wheelers vs. Four-Wheelers and mapped 98 distinct models to parent automotive brands (Toyota, Honda, Hyundai, Maruti Suzuki, Royal Enfield, Bajaj, etc.).

---

## 📊 Core Analytical Findings

### 1. Primary Valuation Drivers
* **Original Showroom Price:** Strongest linear correlation with final selling price (**$r = 0.88$**), proving initial vehicle tier is the main pricing determinant.
* **Vehicle Age vs. Mileage:** Manufacturing year exhibits a positive correlation with price (**$r = +0.24$**), whereas odometer mileage has a near-neutral impact (**$r = +0.03$**), demonstrating that age accelerates depreciation significantly faster than kilometers driven.

### 2. Brand Depreciation Resilience
* **Top Value Retainers:** **Royal Enfield (~26.1% average depreciation)** and **Hyundai (~29.1% average depreciation)** retain the highest percentage of resale value due to strong enthusiast demand and high secondary liquidity.
* **Luxury Depletion:** Premium utility vehicles (e.g., Toyota Land Cruiser) experience the highest absolute depreciation (losing up to ₹57.60 Lakh) despite retaining substantial terminal value.

### 3. Market Composition & Ownership
* **Top Selling Models:** **Honda City (26 units)** leads passenger cars; **Royal Enfield Classic 350 (7 units)** leads two-wheelers.
* **Fuel & Transmission:** Petrol vehicles represent **79.4% (239 units)**; Manual gearboxes represent **86.7% (261 units)**.
* **Ownership Tiers:** First-owner vehicles dominate the inventory (**96.3%**, 290 units).

### 4. Post-2014 Fleet Expansion
* Modern vehicles (manufactured >2014) constitute **48.8% (147 units)** of total market supply, commanding an average resale premium of **₹5.77 Lakh** compared to **₹3.60 Lakh** for pre-2015 vehicles.

---

## 💡 Strategic Takeaways
1. **Algorithmic Pricing:** Used car aggregators should weight vehicle age and ex-showroom price brackets heavily over raw mileage in appraisal models.
2. **Inventory Sourcing:** Dealerships should prioritize sourcing high-retention brands (Royal Enfield, Hyundai, Maruti Suzuki) to maximize turn rates and protect trade-in margins.
3. **Consumer Insights:** Buyers seeking value should consider 4–6 year old high-end petrol sedans, where initial steep depreciation curves provide favorable price-to-utility ratios.

---

## 👤 Author
* **Osman Ahmed Khan**
* GitHub: [@OsmanKhanIO](https://github.com/OsmanKhanIO)
