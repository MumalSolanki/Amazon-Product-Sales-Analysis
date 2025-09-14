 **Amazon Product Sales Analysis** 
 
This project is focused on exploration  of e-commerce sales data aimed at uncovering actionable insights into product performance, discount strategies, and pricing patterns. Using a dataset of **42,675 rows and 17 columns** sourced from Kaggle, the analysis leverages **Python, Pandas, and Plotly** to process, visualize, and interpret large-scale product information in a structured and reproducible way.

---

## Motivation

E-commerce platforms like Amazon generate massive volumes of data on product listings, customer ratings, reviews, and discounts. For sellers, this information holds the key to understanding market dynamics: which products resonate most with customers, how discounts influence purchasing behavior, and which categories demonstrate stronger price competition. This project was created to answer these questions through clear, data-driven analysis and to serve as a foundation for more advanced applications such as recommendation systems or dynamic pricing strategies.

---

## Dataset

The dataset contains product-level attributes, including:

* **Product title**
* **Category**
* **Ratings and reviews**
* **Original and discounted prices**
* **Discount percentages**
* **Best-seller status**

This diversity allows exploration across multiple business dimensions, from customer sentiment (ratings) to financial levers (discounts and pricing).

---

## Methodology

The workflow followed a structured **Exploratory Data Analysis (EDA)** approach:

1. **Data Cleaning & Preparation**
   Missing values were handled, column types standardized, and irrelevant features filtered.

2. **Descriptive Analysis**
   Summary statistics and distributions were examined to understand the overall dataset profile.

3. **Visualization & Insights**
   Plotly was used to create interactive visualizations, supplemented with static screenshots for documentation. Key plots include:

   * **Top 10 Products by Rating (Bar Chart):** Identifies highest-rated products, useful for benchmarking customer satisfaction.
   * **Average Discount % by Category (Bar Chart):** Reveals how discounting strategies differ across categories, highlighting which categories are more aggressive in promotions.
   * **Original vs Discounted Price by Category (Scatter Plot):** Compares pricing gaps, showing where discounts lead to significant deviations from listed prices.

---

## Key Findings

* **Top Products:** A handful of products consistently achieve higher ratings, suggesting strong brand perception or quality consistency.
* **Discount Patterns:** Categories such as electronics and apparel exhibit higher average discounts, aligning with industry trends of competitive pricing and frequent promotions.
* **Price Relationships:** In some categories, the discounted price remains close to the original, while in others, deep cuts suggest strategies to clear inventory or drive volume sales.

These insights provide a foundation for sellers to refine **pricing strategies, discount allocation, and product positioning**.

---

## Technical Stack & Structure

* **Languages & Libraries:** Python, Pandas, NumPy, Plotly
* **Notebook Environment:** Google Colab
* **Repository Layout:**

  * `data/` for datasets or download instructions
  * `notebooks/` for the analysis notebook
  * `figures/` for static plots and screenshots
  * `requirements.txt` for dependencies
  * `README.md` for documentation

This organization mirrors industry practices, making the project reproducible and extendable.

---

## Future Extensions

Potential next steps include:

* **Interactive Dashboard:** Building a Streamlit or Plotly Dash interface for real-time filtering by category, rating, or discount.
* **Machine Learning Models:** Predicting product success based on attributes like price, discount, and rating.
* **Clustering:** Segmenting products into groups (e.g., “premium but low-discount,” “budget with high-discount”) for strategic decision-making.
* **Time-Series Trends:** If sales or review timestamps become available, analyzing seasonality and long-term dynamics.

---

## Conclusion

This project demonstrates how raw product sales data can be transformed into actionable insights through systematic analysis. By combining **data cleaning, visualization, and interpretation**, it highlights the intersection of **technical skills** (Python, Pandas, Plotly) and **business relevance** (pricing, promotions, product positioning). The repository provides a solid foundation for both showcasing analytical skills and serving as a springboard for deeper e-commerce analytics applications.



