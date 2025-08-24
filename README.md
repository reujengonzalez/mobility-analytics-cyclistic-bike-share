# Cyclistic Bike Share (Mobility Analytics) \[Excel, R, Tableau]

## 📌 Overview

This project is based on the **Cyclistic Bike Share dataset** (from the Google Data Analytics Capstone). The goal was to analyze **usage patterns between casual riders and annual members** to support **marketing strategies** that encourage casual users to convert into paid members.

Using **Excel** and **R** for cleaning and analysis, and **Tableau** for visualization, I created clear data stories highlighting seasonal trends, rider behaviors, and membership differences.

---

## 🎯 Objectives

Key goals of the project:

* Compare **ride frequency** between casual riders and members.
* Identify **seasonal and weekly usage patterns**.
* Analyze **ride duration trends** across user types.
* Provide **data-driven recommendations** for Cyclistic’s marketing team.

---

## 📂 Dataset Description

* **Source:** Divvy/Cyclistic Public Bike Share Data
* **Size:** 12 months of trip records (\~5 million rows)
* **Main Features:**

  * `ride_id`, `rideable_type`, `started_at`, `ended_at`
  * `ride_length`, `day_of_week`, `member_casual`
* **Preprocessing with Excel & R:**

  * Removed duplicates and null values
  * Standardized date-time formats
  * Created new fields: `ride_length`, `day_of_week`
  * Filtered out outliers (trips <1 min or >24 hrs)

---

## 🛠️ Tools & Techniques

* **Excel**

  * Initial cleaning, descriptive statistics, pivot analysis
* **R**

  * Data wrangling with `dplyr`
  * Ride duration calculations, grouping, and aggregation
* **Tableau**

  * Static visualizations (no dashboard)
  * Charts: line charts (seasonal trends), bar charts (membership comparison), heatmaps (time-of-day analysis)
  * Calculated fields for average ride length and weekly trends

---

## 📊 Key Insights

* **Seasonality:** Casual riders peaked in summer, while members maintained steady usage year-round.
* **Ride Duration:** Casual riders took **longer trips on average** compared to members.
* **Day-of-Week Trends:**

  * Members rode more on **weekdays** (commuting patterns).
  * Casual riders preferred **weekends** (leisure activity).
* **Bike Type:** Members favored **classic bikes**, while casual riders leaned more toward **docked bikes**.

👉 [View Tableau Visualizations](https://public.tableau.com/app/profile/reujen.gonzalez/viz/Book2_17515582639420/TotalRidesperRiderType)

---

## ⚡ Challenges & Solutions

* **Challenge:** Dataset size (millions of rows) exceeded Excel limits.
  **Solution:** Used **R** for scalable data cleaning and transformation.

* **Challenge:** No interactive dashboard for exploration.
  **Solution:** Focused on well-designed **static Tableau visuals** to communicate findings effectively.

---

## 🔍 How to Explore

1. **Visualizations** – See Tableau visuals [here](https://public.tableau.com/app/profile/reujen.gonzalez/viz/Book2_17515582639420/TotalRidesperRiderType)
2. **R Scripts** – Check the `scripts/` folder for data cleaning and transformations.
3. **Case Study Report** – Read the detailed write-up in `mobility-analytics-case-study.docx`.

---

## 🚀 Next Steps

* Build a full **interactive Tableau dashboard** for deeper filtering and exploration.
* Add **geospatial analysis** (map-based visualization of popular routes).
* Conduct **predictive modeling** to estimate membership conversion likelihood.
* Test **seasonal marketing strategies** using data-backed rider segmentation.

---

📌 **Author:** Reujen Gonzalez

🔗 **Portfolio Website:** [Link](https://reujengonzalez.github.io/) | **LinkedIn:** [Link](https://www.linkedin.com/in/reujen-river-gonzalez-878356350/) | **GitHub:** [Link](https://github.com/reujengonzalez)
