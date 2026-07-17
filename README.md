# 📊 Global Marketing Campaign Performance Analytics Portfolio
> **An End-to-End Advanced Data Engineering and Interactive Business Intelligence Pipeline Framework over 200,000 Campaign Records.**

---

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white" alt="Plotly"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</p>

---

## 🚀 Business Case & Executive Problem Statement
Organizations spend significant capital across multiple digital channels (Email, Social Media, Search, Influencer, and Display ads) to drive product sales and user engagement. However, optimizing a marketing budget requires knowing precisely which campaigns, channels, audience demographics, and geographic regions deliver the highest profitability.

The objective of this project is to implement a complete production-grade data analytics pipeline using **Python (Pandas, NumPy, Seaborn, and Plotly)** to evaluate marketing portfolio performance, extract key financial efficiency markers, and deliver multi-dimensional interactive dashboards that facilitate data-driven decision-making for executive marketing management.

---

## 🛠️ Technological Tool Stack & Systems Engineering
*   **Data Processing and Manipulation Engine:** `Python 3.12` / `Pandas` (DataFrames, aggregations, vector sanitization) / `NumPy` (Vectorized mathematical conditions).
*   **Statistical Data Visualization Engine:** `Seaborn` & `Matplotlib` (Static distribution profiling, bar plots, distribution matrices).
*   **Advanced Interactive Business Intelligence (BI):** `Plotly Express` (High-dimensional 3D rotatable spaces, hierarchical sunburst drill-downs).

---

## ⚙️ Data Preprocessing & Advanced Feature Engineering
Raw enterprise marketing records are rarely formatted perfectly for statistical engines. This project cleanses text string corruptions, converts unformatted dates, and engineers major industry-standard marketing efficiency metrics to evaluate unit costs:

1. **Currency String Sanitization:** Stripped currency markers (`$`) and numerical string denominators (`,`), casting object data columns into standard statistical numerical floating-point systems (`float64`).
2. **Chronological Pipeline Alignment:** Converted text dates into actual object series types to support time-series segmentation.
3. **Engagement Rate (ER):** Engineered the interaction ratio tracking how effectively visibility translates to direct user clicks.
   $$\text{Engagement Rate} = \left(\frac{\text{Clicks}}{\text{Impressions}}\right) \times 100$$
4. **Total Conversions Delivered:** Calculated the volume of users successfully converted based on click rates and conversion margins.
   $$\text{Total Conversions} = \text{Clicks} \times \text{Conversion\_Rate}$$
5. **Cost Per Click (CPC):** Safely mapped the micro-unit marketing budget spent to generate a single user action.
   $$\text{CPC} = \frac{\text{Acquisition\_Cost}}{\text{Clicks}}$$
6. **Cost Per Acquisition (CPA):** Built a macro-efficiency indicator isolating the total dollar amount required to capture one paying consumer while using conditional safeguards (`np.where`) to prevent runtime division-by-zero errors.
   $$\text{CPA} = \frac{\text{Acquisition\_Cost}}{\text{Total Conversions}}$$
---

## 📈 Key Insights & Strategic Discoveries

### 1. Executive Performance Dashboard
*   **Average Campaign Conversion Rate:** 8.01%
*   **Average Audience Engagement Rate:** 14.04%
*   **Total Portfolio Marketing Spend:** $5,039,989,638.00
*   **Total Acquired Customers Volume:** 17,609,160 users

### 2. Strategic Campaign Type & Profitability Ranking
Grouping the records by campaign type reveals which broad communication methodologies produce the highest Return on Investment (ROI):

| Campaign Strategy Type | Average ROI Multiplier | Average Conversion Rate | Average Engagement Rate |
| :--- | :---: | :---: | :---: |
| **Influencer Marketing** | **5.011** | **8.03%** | **14.03%** |
| **Search Campaigns** | 5.008 | 8.00% | 13.99% |
| **Display Advertisements** | 5.006 | 8.01% | 14.13% |
| **Email Newsletters** | 4.994 | 7.98% | 13.95% |
| **Social Media Ads** | 4.991 | 8.01% | 14.10% |

### 3. Digital Distribution Channel Efficiencies
Analyzing specific broadcasting platforms clarifies exactly where media budgets are optimized:

| Media Channel Used | Average ROI Multiplier | Average Conversion Rate | Performance Status |
| :--- | :---: | :---: | :--- |
| **Facebook** | **5.019** | **7.99%** | 🏆 **Top Performer** |
| **Corporate Website** | 5.014 | 8.02% | High Return |
| **Google Ads** | 5.003 | 8.02% | Stable Baseline |
| **Email Channel** | 4.996 | 8.03% | Average Yield |
| **YouTube Videos** | 4.994 | 7.99% | Moderate Yield |
| **Instagram** | 4.989 | 7.99% | Underperforming |

---

## 🔮 Data Visualizations Highlight Space

### Multi-Dimensional Interactive 3D Scatter Matrix
Built with Plotly Express over a 2,000-row randomized sample to balance high performance and accurate data distribution modeling. It allows stakeholders to rotate, scale, and filter across **Clicks (X)**, **ROI (Y)**, and **Engagement Rate (Z)** simultaneously while color-coding by **Conversion Rate** or financial cost efficiency.

<img width="806" height="350" alt="Screenshot 2026-07-13 185307" src="https://github.com/user-attachments/assets/6c4ecbe4-46a1-4207-87d5-2eb79f214e29" />


<img width="769" height="347" alt="Screenshot 2026-07-13 184918" src="https://github.com/user-attachments/assets/2f20b806-0481-4da9-819a-73c83a75e944" />


<img width="803" height="367" alt="Screenshot 2026-07-13 184845" src="https://github.com/user-attachments/assets/b1e62e5c-9588-4395-9a2f-572876fda423" />


---

## 🏁 Conclusion & Future Roadmap
This analytics framework successfully demonstrates how raw, cluttered enterprise data can be systematically cleaned, engineered, and transformed into high-impact visual intelligence. By shifting from static 2D snapshots to high-dimensional interactive analysis, data-driven teams can instantly isolate marketing budget waste, capture hidden demographic trends, and allocate capital efficiently to maximize net returns.

### 🔮 Planned Next Steps & Enhancements
To evolve this project into a full-scale automated marketing platform, the future roadmap includes:
*   **Predictive Revenue Modeling:** Integrate a machine learning module (using `scikit-learn` or `XGBoost`) to predict future campaign ROI based on historical audience demographics and spend.
*   **Time-Series Forecasting:** Implement seasonal cohort analysis to help teams dynamically adjust budget allocation leading up to major shopping holidays or quarters.
*   **Live Stream Pipeline:** Transition from static CSV files to a live cloud pipeline (using AWS or Google BigQuery) to ingest real-time ad network logs instantly.

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/priya-spacex">Priya Dey</a> — Data Analytics Portfolio © 2026
</p>
<p align="center">
  <a href="#-global-marketing-campaign-performance-analytics-portfolio">🔼 Back to Top</a>
</p>
