# 🛒 Supermarket Sales EDA Project

### Author: [Shaibaj Shaikh](#)

This project performs an **Exploratory Data Analysis (EDA)** on supermarket sales data to uncover insights about **branch performance**, **customer behavior**, **product popularity**, and **sales trends** over time.

---

## 📁 Project Overview

The goal of this project is to analyze supermarket transactional data and identify:
- Which branches perform the best  
- The most popular product categories  
- Spending patterns based on gender  
- Preferred payment methods  
- Seasonal or monthly trends in sales  

This EDA helps businesses understand customer behavior and make data-driven decisions to improve revenue and customer satisfaction.

---

## 🧩 Dataset Information

**Dataset Name:** Supermarket Sales Dataset  
**Source:** [Kaggle - Supermarket Sales](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales)

**Features include:**
- **Invoice ID:** Unique identifier for each transaction  
- **Branch:** Branch of the supermarket (A, B, C)  
- **City:** Location of the branch  
- **Customer Type:** Member or Normal customer  
- **Gender:** Male/Female  
- **Product Line:** Product category  
- **Unit Price & Quantity:** Price per item and number of items purchased  
- **Tax & Total:** Calculated tax and total amount  
- **Date & Time:** When the purchase occurred  
- **Payment:** Mode of payment (Cash, Credit card, E-wallet)  
- **Rating:** Customer satisfaction score  

---

## 🧹 Data Cleaning Steps

- Removed missing or duplicate entries  
- Converted date and time columns to appropriate formats  
- Created new time-based features (Month, Day, Hour)  
- Verified data types and ensured consistency  

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis
- Distribution of total sales, ratings, and product lines  
- Count plots for payment types and gender distribution  

### 🔹 Bivariate Analysis
- Sales vs. Branch  
- Gender vs. Total Sales  
- Product Line vs. Gross Income  

### 🔹 🔥 Correlation Heatmap
- Visualized relationships between numerical features like `Total`, `Tax`, and `Rating`

### 🔹 ⏳ Time-Based Analysis
- Monthly and weekly sales trends  
- Hourly sales performance for each branch  

---

## 🧠 Key Insights

- **Branch C** generated the **highest total sales**  
- **Female customers** spent slightly more on average  
- **Food and Beverages** and **Fashion Accessories** were **top-selling categories**  
- **E-wallet** was the **most preferred payment method**  
- **Sales peaked in January**, possibly due to seasonal shopping  

---

## 🛠️ Technologies Used

- **Python 3.x**  
- **Jupyter Notebook**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical operations  
- **Matplotlib / Seaborn** – Data visualization  

---

## 📈 Visualizations

The notebook includes:
- Bar charts and histograms  
- Correlation heatmap  
- Time-series plots  
- Gender and category comparison plots  

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone  https://github.com/shaibajshaikh/supermarket-sales-eda.git
   cd supermarket-sales-eda
   ```

2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook "EDA PROJECT.ipynb"
   ```

---

## 📜 License

This project is licensed under the **MIT License** – you’re free to use, modify, and distribute it with attribution.

---

## 💬 Contact

For any questions or collaborations, feel free to reach out:  
📧 ** shaibazs377@gmail.com
