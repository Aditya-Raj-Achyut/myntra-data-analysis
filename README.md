# 🛍️ Myntra Data Analysis Project

This project focuses on analyzing Myntra's fashion product data using Python and Google Colab.  
The goal is to extract key insights about brands, pricing, discounts, and customer ratings.

---

## 📊 Project Overview

This analysis explores:
- Which brands have the most products listed on Myntra
- How discount percentage affects ratings
- Relationship between marked price and discounted price
- Average discount and rating by brand
- Top performing brands in terms of ratings and discounts

---

## 🧰 Tools & Libraries Used

- **Python**
- **Pandas** – Data manipulation  
- **NumPy** – Numerical analysis  
- **Matplotlib** & **Seaborn** – Visualization  
- **Google Colab** – Development environment  

---

## 🧹 Data Cleaning Steps

1. Removed duplicate columns and rows  
2. Dropped unnecessary columns like product links and image URLs  
3. Filled missing values where necessary  
4. Created a new column `price_diff` = `marked_price - discounted_price`  

---

## 📈 Key Insights

- 🔝 **Top Brands:** The dataset shows which brands dominate Myntra listings  
- 💸 **Discount Trends:** Some brands offer significantly higher discounts  
- ⭐ **Ratings:** Higher discounts don’t always mean higher ratings  
- 📊 **Correlation:** Visualized correlation between price, rating, and discount  

---

## 📉 Visualizations

The notebook includes:
- Top 10 brands by number of products  
- Average discount by brand  
- Average rating by brand  
- Scatter plots for `discounted_price vs rating`  
- Correlation heatmap  

---

## 🚀 How to Run

1. Open the notebook on Google Colab  
2. Upload the dataset (`data.csv`)  
3. Run all cells sequentially  
4. Explore the graphs and insights  

---

## 📂 Dataset Columns

`product_name`, `brand_name`, `rating`, `rating_count`, `marked_price`,  
`discounted_price`, `sizes`, `discount_percent`, `discount_amount`,  
`brand_tag`, `product_tag`

---

## 🧩 Future Improvements

- Add sentiment analysis on product reviews (if available)  
- Automate discount trend tracking  
- Build a small dashboard using Streamlit  

---

## 👨‍💻 Author

**Aditya Raj**  
_Data Analyst | Python & SQL Enthusiast_  
🔗 [GitHub Profile](https://github.com/Aditya-Raj-Achyut)

