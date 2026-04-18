# 🗽 NYC Airbnb Market Analytics: A Geospatial & Pricing Study

### 📋 Project Overview
This project is a high-level Exploratory Data Analysis (EDA) investigating the 2024 New York City Airbnb landscape. Moving beyond basic statistics, I utilized Python to analyze pricing dynamics, borough-wise cost efficiency, and the professionalization of the short-term rental market.

---

### 🛠️ Technical Workflow
* **Data Cleaning:** Handled missing coordinates, corrected data types for 20k+ records, and resolved duplication issues to ensure 100% analytical accuracy.
* **Fixing Outliers:** Identified extreme price points (up to $100,000) via Boxplots and implemented a filtering strategy (< $2,000) to focus on core market trends.
* **Feature Engineering:** Developed a custom **"Price per Bed"** metric to identify true cost-efficiency across different neighborhood groups.
* **Geospatial Mapping:** Leveraged Latitude and Longitude data to visualize listing density and room-type distribution across NYC.

### 🎨 Data Visualization & Insights
* **Correlation Heatmaps:** Analyzed relationships between price, availability, and review frequency using Seaborn Heatmaps.
* **Borough Distribution:** Proved **Manhattan** as the luxury leader ($208 avg) vs. the **Bronx** as the budget-friendly alternative ($108 avg).
* **Host Behavior Analysis:** Identified a massive spike in 365-day availability, proving the market is dominated by **professional, full-time hosts** rather than casual home-sharers.
* **Inverse Feedback Loop:** Discovered that lower-priced units attract significantly higher review volumes, suggesting higher guest turnover.

### 🧰 Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Tool:** Jupyter Notebook
