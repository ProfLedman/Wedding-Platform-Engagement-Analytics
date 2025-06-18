# 💍 Wedding Platform Engagement Analytics

This project analyzes user and supplier interactions on a wedding services marketplace platform, focusing on how couples engage with vendors (suppliers) across different stages of the First Contact Response (FCR) funnel. Through structured data analysis, we uncover key engagement metrics, trends, and drop-off points to help inform platform improvements and supplier performance strategies.

---

## 📌 Key Business Questions

1. **Supplier Tiering**: How does the supplier read rate differ by supplier tier? Are there any engagement trends?
2. **Top & Bottom Performers**: Who are the top 5 and bottom 5 responding suppliers in France (FR), based on those who received ≥10 enquiries?
3. **Couple Behavior in GB**: What does the distribution of initial enquiries per wedding look like in Great Britain (GB)? How do the mean and mode compare?
4. **Enquiry Trends Over Time**: What do daily enquiry levels reveal across GB and FR? Are there clear seasonal or weekly patterns?
5. **Funnel Drop-off Analysis**: Which FCR funnel step in GB sees the highest drop-off rate? What might explain this disengagement?

---

## 🧠 Skills & Tools Demonstrated

| Category               | Tools / Techniques                                       |
|------------------------|----------------------------------------------------------|
| Data Wrangling         | `pandas`, datetime parsing, missing data handling        |
| Exploratory Analysis   | Aggregation, grouping, descriptive statistics            |
| Data Visualization     | `matplotlib`, `seaborn`                                  |
| Funnel Analytics       | Stepwise conversion, drop-off computation                |
| Business Interpretation| Engagement patterns, supplier behavior, UX insights      |
| Reproducibility        | Modular notebook design and full documentation           |

---

## 📈 Summary of Key Findings

- **Higher Tier = Higher Engagement**: Supplier tiers 2.0 and 4.0 had a perfect read rate (100%), showing strong responsiveness, while the "Unknown" tier had the lowest (31%).
- **Supplier Response Disparity (FR)**: Top 5 FR suppliers had a near 100% response rate; bottom 5 had virtually none, despite each receiving ≥10 enquiries.
- **Couple Enquiry Behavior (GB)**: Most couples sent 1–3 enquiries, with a **mean of 2.07** and **mode of 1**, suggesting highly targeted outreach.
- **GB vs FR Activity**: GB consistently showed higher daily enquiry volumes, suggesting greater platform engagement or market penetration.
- **Funnel Drop-Off**: The largest conversion drop occurred at the **cm2_check** step, where only ~8% of users continued, highlighting a key disengagement point after supplier response.

---

## 📂 Project Structure

wedding-platform-engagement/
│
├── data/
│ ├── FCR_enquiries.csv
│ └── FCR_enquiries_descriptions.csv
│
├── visuals/
│ └── supplier_read_rates.png
│ └── enquiry_distribution_gb.png
│ └── daily_enquiries_gb_fr.png
│ └── funnel_drop_off_gb.png
│
├── notebook/
│ └── wedding_supplier_engagement_analysis.ipynb
