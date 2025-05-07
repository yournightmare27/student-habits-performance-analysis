# Student Performance Clustering & Behavioral Insight Dashboard

## Overview

This project explores how behavioral patterns such as study time, sleep habits, mental health, and digital consumption influence academic performance among students. By applying clustering techniques and developing visual analytics in Tableau, I uncovered key insights that could guide student support strategies, time management plans, and even AI-driven educational recommendations.

## Tools & Technologies

* **AI Studio (Altair 2025)**: For data cleaning, correlation analysis, and K-Means clustering
* **Tableau**: For creating interactive, professional-grade data visualizations
* **Pandas, Excel**: (for preprocessing & exporting cluster data where needed)

## Key Objectives

* Identify distinct behavioral clusters among students
* Analyze the correlation between study hours and exam scores
* Explore how mental health impacts academic performance
* Assess the effects of screen time (Netflix, social media) on sleep

---

## Process Summary

1. **Data Ingestion & Cleaning**

   * Imported a CSV file containing student data with variables such as study hours, sleep hours, attendance, exam scores, and more
   * Removed non-numerical attributes for clustering (e.g., gender, ID)

2. **Correlation Analysis**

   * Performed Pearson correlation to determine which features most impact `exam_score`
   * Found `study_hours_per_day`, `attendance_percentage`, and `mental_health_rating` as most relevant

3. **K-Means Clustering**

   * Applied K-Means algorithm (k=5) to segment students
   * Created new feature: `cluster_label` assigning levels such as "Excellent", "Good", "Average", "Low", "Poor"

4. **Tableau Visualizations**

   * **Combo Chart**: Study Hours vs. Exam Score by Cluster (Bar + Line)
   * **Scatter Plot**: Exam Score vs. Study Hours (colored by performance label)
   * **Bubble Chart**: Mental Health vs. Exam Score/Study Time

---

## Key Insights

* **3.5 to 4.5 Hours of Study/Day** yields the highest average exam scores.
* Students with **high mental health ratings** tend to perform better academically.
* There is a **negative trend** between screen time and sleep, especially among lower-performing clusters.
* Clustering revealed that **time management and well-being go hand-in-hand** with academic success.

---

## Portfolio Value

This project showcases my ability to:

* Work with real-world behavioral data
* Perform unsupervised learning (K-Means)
* Interpret and visualize complex multi-dimensional datasets
* Communicate findings in a business- and employer-friendly format

## Try the Interactive Version (Optional)

> \[View on Tableau Public (link here)]

---

## Contact

**Tanya Sasnouskaya**
AI Graduate Student | BS in Cybersecurity & Data Visualization Enthusiast
[LinkedIn](#) | [GitHub](#) | [Email](#)

---
