# 👗 Women Clothing E-commerce Reviews Analysis

## 📊 Overview

This project analyzes customer reviews and purchase behavior from a women's clothing e-commerce platform. With a dataset of **23,486 entries** and **19 columns**, we aim to uncover customer sentiment, identify top-performing products, and provide business insights that can improve product offerings and customer satisfaction.

- 🧹 Data Cleaning: Python (Pandas, NumPy)
- 📈 Visualization: Tableau
- 🧠 Insights: Product preferences, customer segmentation, sentiment patterns

---

## 🗂 Dataset Summary

| Column Name              | Description                                                |
|--------------------------|------------------------------------------------------------|
| `Clothing ID`            | Unique identifier for each clothing item                  |
| `Age`                    | Age of the reviewer (18–99)                               |
| `Title`                  | Summary title of the review (16% missing)                 |
| `Review Text`            | Full content of the review (4% missing)                   |
| `Rating`                 | Rating from 1 to 5 stars                                  |
| `Recommended IND`        | Binary flag: 1 if recommended, 0 otherwise                |
| `Positive Feedback Count`| Number of positive responses                              |
| `Division/Department/Class` | Product category hierarchy                          |

---

## 🧹 Data Cleaning Highlights (Python)

- Handled missing data in `Title` and `Review Text`
- Classified age into 3 segments:
  - **Young (18–30)**
  - **Middle-aged (31–60)**
  - **Elderly (61+)**
- Applied basic sentiment tagging based on review tone (positive: 1, negative: -1)
- Mapped clothing popularity and review distribution by product and age group

---

## 📊 Key Insights

- 👩 **Middle-aged women** (30–50) are the largest and most critical customer segment, with the lowest average rating (4.17).
- ❤️ Customers across all age groups write equally detailed reviews.
- 👚 **Most purchased items**: Dresses, Knits, Blouses, and Fine Gauge items (IDs: 1078, 1094, 1081, 862, 895…).
- ⭐ **High rating (≥ 4)** is a strong signal of product satisfaction and trust.
- ❌ **Common complaints** found via Word Cloud:
  - Lingerie: "runs small", "poor fit", "itchy tags"
  - Jackets: "poor quality", "poor execution"
  - Dresses/Pants: "too tight" or "potato sack"
- 🔄 **Correlation between Rating and Recommendation**:
  - 99% of positive reviewers recommend the product
  - 95% of negative reviewers do **not** recommend it
- ✍️ **Longer reviews** tend to receive more likes — a potential loyalty incentive trigger (e.g. discounts, coupons)

---

## 📈 Tableau Visualizations

Interactive visual dashboards are built with Tableau to explore:
- Age vs Rating distribution
- Product popularity across segments
- Sentiment distribution by product category
- Word clouds for top complaints

📌 [View Tableau Dashboard (link placeholder)](https://public.tableau.com/...)

---

## 💡 Business Implications

- Tailor product development and marketing campaigns to **middle-aged women** — the most engaged yet critical customers
- Improve quality control for **undergarments** and **jackets** based on detailed complaints
- Promote top-loved products (with high ratings and recommendation rates)
- Encourage meaningful reviews by offering incentives to detailed contributors
- Leverage sentiment analytics to monitor customer satisfaction over time

---

## 🧰 Tech Stack

| Task                  | Tools Used               |
|-----------------------|--------------------------|
| Data Cleaning         | Python (Pandas, NumPy)   |
| Sentiment Mapping     | Python                   |
| Visualization         | Tableau                  |
| Word Cloud Analysis   | Python (wordcloud)       |

---

## 🏁 Conclusion

By analyzing female customers' purchase and review behavior, we gain a better understanding of:
- What products different age groups prefer
- How product quality and fit affect customer satisfaction
- The role of reviews and recommendations in driving future sales

These insights enable e-commerce platforms to better **segment customers**, **optimize inventory**, and **improve product design** based on real feedback.

---

## 🏆 Achievement

✨ This project was selected as part of the **Top 30 Finalists** in the **RMIT Business Analytics Champion**.

---

