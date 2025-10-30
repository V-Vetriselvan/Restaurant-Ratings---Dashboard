# ⭐ Restaurant Ratings Dashboard

## 📊 Overview

This dashboard provides an in-depth analysis of consumer feedback and restaurant performance based on ratings data. It is designed to help restaurant owners and marketing teams understand customer demographics, identify rating strengths and weaknesses across different cuisines, and benchmark service quality.

## ✨ Key Metrics & Consumer Base

The top row summarizes the scale and core metrics of the rating dataset:

- **Total Consumers:** **138** (Total unique individuals who provided ratings)
- **Total Ratings Volume:** **1161** (Total number of individual ratings recorded)
- **Average Overall Rating:** **1.20** (Mean rating across all restaurants/visits)
- **Distinct Restaurant Rated:** **130** (Total number of unique restaurants covered)
- **Average Consumer Age:** **27.30** (Mean age of the rating consumers)

---

## 📈 Analysis & Insights

### 1. Rating Consistency and Gaps

- **Rating Trends Across Cuisines:** Shows the average ratings for food, service, and overall experience across different cuisine types (e.g., American, Italian, Bakery). Ratings appear remarkably consistent across all categories, hovering around **1.2** for overall and food, and slightly lower for service.
- **Comparison of Rating Gaps:** Plots the difference between overall, food, and service ratings across specific cities (Cuernavaca, Jiutepec, San Luis Potosí, Ciudad Victoria). This highlights cities where service or food quality might be lagging behind the overall perception.

### 2. Consumer Demographics and Behavior

- **Consumer Count by Age Distribution:** Illustrates that the vast majority of consumers providing ratings fall into the **20-24 age group**, with participation dropping sharply in older segments.
- **Donut - Smoker:** Shows the consumer base split by smoking status. A large majority of consumers **(78.99%) are non-smokers**, which is valuable demographic information for targeted marketing and lounge planning.
- **Occupation-Specific Rating Performance:** Breaks down average ratings by the consumer's occupation (**Employed, Student, Unemployed**). **Students** provide the highest average food rating (**1.46**), while **Unemployed** consumers gave a zero rating across the board, suggesting data gaps or specific biases.

### 3. Supply and Category Focus

- **Bar - Supply:** Uniformly shows **130** for all cuisine categories (American, Italian, Bakery, etc.). This likely indicates the total number of distinct restaurants available in the dataset for each category, or a constant supply metric for the analysis.

---

## 🎯 Strategic Recommendations

1.  **Service Quality Focus:** Although ratings are consistent, investigate the minor dip in **Average Service Rating** across all cuisines (e.g., 1.1) and cities, as this is the most common area for improvement.
2.  **Target Young Consumers:** Given the dominance of the **20-24 age group** in the consumer count, prioritize marketing and menu adjustments that appeal to this demographic.
3.  **Investigate Rating Gaps:** Perform a deeper analysis on the specific cities identified in the 'Comparison of Rating Gaps' chart to understand why food or service ratings diverge from the overall rating.
4.  **Validate Unemployed Data:** Review the source data for the 'Unemployed' segment, as the zero rating is likely an anomaly that requires cleaning or exclusion for accurate metric reporting.

---

## 🛠️ Data & Technical Details

- **Data Source:** Consumer Survey / Aggregated Rating Platform Data (Simulated)
