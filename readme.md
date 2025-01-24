# 🛍️ **Customer Transaction Data Analysis** 
### 📊 **A deep dive into customer behavior, sales trends, and product popularity using Exploratory Data Analysis (EDA)**

---

## 📖 **Overview**

This project analyzes an **eCommerce transactions dataset**, uncovering valuable **business insights** to drive strategic decisions. We explore **customer demographics, product trends, and regional sales distributions** using data analysis and visualization techniques.

---

## 📂 **Project Structure**

### 📁 **Notebooks & Reports**
- 📒 `Likhith_SV_EDA.ipynb` → **Exploratory Data Analysis (EDA)** notebook
- 📜 `Likhith_SV_EDA.pdf` → **EDA Summary Report**
- 📒 `Likhith_SV_Clustering.ipynb` → **Customer Segmentation using Clustering**
- 📜 `Likhith_SV_Clustering.pdf` → **Clustering Analysis Report**
- 📒 `Likhith_SV_Lookalike.ipynb` → **Lookalike Customer Analysis**
- 📜 `Likhith_SV_Lookalike.csv` → **Lookalike Customer Dataset**

### 📁 **Datasets**
- 📄 `Customers.csv` → **Customer details dataset**
- 📄 `Products.csv` → **Product information dataset**
- 📄 `Transactions.csv` → **Transaction records dataset**

---

## 📊 **Key Business Insights**

✔️ **Top 5 Customer Regions:**
1️⃣ South America - **59 customers**  
2️⃣ Europe - **50 customers**  
3️⃣ North America - **46 customers**  
4️⃣ Asia - **45 customers**

✔️ **Average Transaction Value:**  
💰 **$689.99** per transaction

✔️ **Most Popular Product Categories:**
- 📚 **Books** - 26 sold
- 🎧 **Electronics** - 26 sold
- 👕 **Clothing** - 25 sold
- 🏠 **Home Decor** - 23 sold

✔️ **Regional Sales Trends:**
- 🌎 **South America** leads in total revenue!  
  - **South America:** **$219,352.56**
  - **Europe:** **$166,254.63**
  - **North America:** **$152,313.40**
  - **Asia:** **$152,074.97**

---

## 📈 **Visualizations & Analysis**

- 📉 **Sales Trends Over Time** → Identifies seasonal patterns and growth trends
- 📊 **Top 5 Most Sold Products** → Highlights customer preferences
- 📦 **Regional Sales Distribution** → Box plot for analyzing sales variations

---

## 🚀 **How to Use This Project**

### 🛠️ **Setup Instructions**

1️⃣ **Clone the Repository:**
```bash

git clone <your-repo-link>
cd <your-repo-folder>
```

### 2. Create a Virtual Environment (Optional)
It is recommended to create a virtual environment to manage dependencies.

```bash
python3 -m venv venv
source venv/bin/activate  # For Windows, use venv\Scripts\activate
```

### 3. Install Dependencies
If you have a `requirements.txt` file, install all dependencies:

```bash
pip install -r requirements.txt
```

Alternatively, install the necessary libraries manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 4. Run the EDA Notebook
To perform Exploratory Data Analysis (EDA):

```bash
jupyter notebook Likhith_SV_EDA.ipynb
```

### 5. Run the Clustering Analysis Notebook
To perform Customer Segmentation using Clustering:

```bash
jupyter notebook Likhith_SV_Clustering.ipynb
```

### 6. Run the Lookalike Customer Analysis
To identify potential high-value customers:

```bash
jupyter notebook Likhith_SV_Lookalike.ipynb
```

### 7. Generate the Reports
Export Jupyter notebooks into PDF or HTML reports for a more polished output:

```bash
jupyter nbconvert --to pdf Likhith_SV_EDA.ipynb
```

## Dependencies
The following libraries are required for the project:

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

Ensure all dependencies are installed in your environment.

## Report Summary
This project provides a comprehensive overview of customer behavior, product trends, and regional sales patterns in an eCommerce context. The analysis includes:

1. **Exploratory Data Analysis (EDA)**
2. **Clustering for Customer Segmentation**
3. **Lookalike Customer Analysis**

Each section offers insights and actionable strategies to optimize eCommerce performance.




