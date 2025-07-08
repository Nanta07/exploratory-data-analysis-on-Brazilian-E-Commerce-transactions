# 📦 E-Commerce Public Dataset - Data Analysis Project

This repository contains a comprehensive exploratory data analysis (EDA) project on an E-Commerce public dataset. The project was initially created as part of an academic assignment, but its depth and versatility make it a valuable public resource for learning data analytics, business insight generation, and storytelling with data.

---

## 📌 Project Overview

The dataset represents a real-world **Brazilian E-Commerce platform** and provides detailed records of orders, customers, sellers, products, payments, and reviews. This project aims to answer key business questions by exploring customer behavior, seller performance, payment trends, delivery efficiency, and user satisfaction.

The goal is to extract insights that can help optimize operational decisions, improve customer experience, and support business strategies through data.

---

> 📦 **Dataset Source**
> The dataset used in this project is sourced from Kaggle and is titled **“Brazilian E-Commerce Public Dataset by Olist.”**
> You can access the original dataset at the following link:
> 🔗 [https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

---

## 🔍 Business Questions Explored

Here are the main business questions addressed in this analysis:

1. **How is the distribution of user review scores?**
2. **Which payment methods are most frequently used by customers?**
3. **How are product sales distributed, and which products are performing well?**
4. **What does the user demographic look like across different states?**
5. **How does product pricing influence user reviews?**
6. **What is the relationship between delivery time and customer satisfaction?**

Each question is supported with data visualizations, trend analysis, and practical conclusions.

---

## 📂 Datasets Used

The following datasets are used in this project (typically from the [Olist E-Commerce Dataset on Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)):

- `products_dataset.csv` – Detailed info on product categories and dimensions.
- `sellers_dataset.csv` – Contains location and identity of sellers.
- `order_items_dataset.csv` – Line-by-line order transaction data.
- `orders_dataset.csv` – General order info (timestamps, status, etc).
- `order_reviews_dataset.csv` – User review scores and comments.
- `customers_dataset.csv` – User IDs and location (city, state).
- `order_payments_dataset.csv` – Payment methods and amounts used per order.

> Note: In the notebook, files are loaded from Google Colab using the `/content/` path.

---

## 🔧 Tools & Libraries Used

- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization
- **Google Colab** – project environment

---

## 📈 Project Structure & Flow

1. **Business Question Identification**
2. **Data Collection** – loading datasets
3. **Data Wrangling** – cleaning and merging data
4. **Exploratory Data Analysis (EDA)** – insights through visualizations
5. **Interpretation** – drawing conclusions from analysis

---

## 📊 Output Preview

The notebook includes:
- Pie charts of payment method distribution
- Histograms of review score frequency
- Heatmaps of correlation between price and satisfaction
- Bar charts of seller/product activity
- State-wise mapping of customer base

All insights are tied back to practical business implications.

---

## 📁 File Included

```

.
├── notebook\_ananta.ipynb         # Jupyter notebook with full EDA process
├── README.md                     # Project documentation
└── \*.csv                         # E-Commerce datasets (external or optional)

```

---

## Setup Environment (Anaconda)
   ```
    conda create --name ecommerce-ds python=3.9
    conda activate ecommerce-ds
    pip install -r requirements.txt
   ```

## Setup Environment (Terminal/Shell)
    ```
    mkdir ecommerce_analysis
    cd ecommerce_analysis
    pipenv install
    pipenv shell
    pip install -r requirements.txt
    ```

## Run Streamlit app (Local)
    ```
    python -m streamlit run dashboard.py
    
    Note: dashboard.py hanya bisa dijalankan dengan menggunakan 'python -m streamlit run dashboard.py'. jangan gunaakn streamlit run dashboard.py karena akan error.
    ```

---

## 👨‍💻 Author

**Ananta Boemi Adji**  
Data & Machine Learning Enthusiast | Computer Engineering Student  
Let's get mutuals on [LinkedIn] | *(linkedin.com/in/ananta-boemi-adji/)*

---

## 📜 License

This project is intended for educational and non-commercial use. Please cite the dataset source if using in publications or derived works.

```
