# Digital Wellness Analytics: Investigating Screen Time Thresholds on User Well-being

## 📌 Project Overview
This repository contains an end-to-end data analytics project exploring how daily social media consumption impacts human anxiety, stress levels, academic performance, and sleep quality. 

Instead of relying on generic surface summaries, this project focuses on **behavioral threshold analysis**—identifying the exact inflection points where user experience shifts from beneficial to critical.

### 🚀 Key Discoveries
* **The 5-Hour Mental Health Inflection Point:** Screen time up to 4 hours behaves as a decompression tool, reducing stress. Beyond 5 hours, anxiety spikes sharply to its sample peak (~5.88), followed by a massive surge in stress at 6+ hours as screen habits begin to conflict with real-world time availability.
* **The Academic Stress Catalyst:** In line with the Yerkes-Dodson psychological law, students with moderate stress levels (level 6) achieved peak average academic performance. Performance drops dramatically when stress overflows past this point.
* **The Age-Neutral Baseline:** True group averages debunked generational assumptions. Early Teens, Late Teens, and Young Adults (19+) all hover around a uniform daily baseline of ~4.5 hours.

---

## 🛠️ Tech Stack & Workflow

### 1. Data Engineering & EDA (Python)
* **Libraries:** `pandas`, `numpy`, `seaborn`, `matplotlib`
* **Tasks Executed:** Missing value mitigation, data scrubbing, feature engineering (cohort segmentation and numerical rounding), and multivariate correlation matrices.

### 2. Business Intelligence & UI Design (Power BI)
* **Features:** Dark-mode executive layout, custom interactive tile slicers, and conditional matrix heatmaps.
* **Key Fix:** Overrode default system sum-aggregation biases within Power BI to implement mathematically accurate **true averages** across overlapping subgroups, eliminating reporting bias for academic and demographic comparisons.

---

## 📊 Dashboard Preview

![Power BI Dashboard Canvas](image_4d7608.png)

---

## 📈 Portfolio Context
*This project forms part of my foundational practical analytics portfolio, bridging core programming concepts with applied business intelligence design.*
