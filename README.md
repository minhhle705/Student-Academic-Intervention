# Student Academic Intervention – Machine Learning Early Warning System

## Overview

This project uses machine learning to identify students who may need additional educational support due to learning disabilities or other academic challenges. It generates an **Intervention Risk (IR) Score** for each student — a continuous value between 0 and 1 — based on performance, engagement, wellness, and contextual factors.

The IR Score is **not** a diagnostic tool. Instead, it serves as an **early warning system** for educators, helping them spot students who might otherwise fall through the cracks, especially in schools with high student-to-teacher ratios and limited resources.

## Objectives

* **Detect At-Risk Students**: Use predictive analytics to identify students likely to require intervention.
* **Prioritize Resources**: Help educators allocate limited support efficiently.
* **Support RTI Framework**: Classify students into Response to Intervention (RTI) tiers.
* **Enable Early Action**: Create a "Tier 2 Watchlist" to catch students trending toward intervention thresholds.

## RTI Tier Classification

The project maps IR scores to RTI tier categories using z-score thresholds:

* **Tier 1** – Core instruction for the majority of students making typical academic progress.
* **Tier 2** – Targeted small-group, in-class interventions for moderate-risk students.
* **Tier 3** – Intensive, individualized interventions for high-risk students.
* **Tier 2 Watchlist** – Early warning category for students trending toward Tier 2, enabling proactive low-cost actions like teacher-parent conversations.

## Files in This Repository
-   `Student-Academic-Intervention.ipynb` - Final notebook with all code, plots, and explanations
-   `Student_Performance_Dataset.csv` – Dataset containing student performance records
-   `README.md` – Project documentation (this file)

## Tools Used

* **Programming Language**: Python
* **Libraries**: Pandas, NumPy, scikit-learn, Matplotlib, Seaborn
* **Environment**: Jupyter Notebook / Google Colab
* **Version Control**: Git & GitHub

