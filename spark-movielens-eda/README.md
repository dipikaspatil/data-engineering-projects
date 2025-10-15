# 🎬 MovieLens EDA using Apache Spark

This project explores the **MovieLens dataset** using **PySpark** for distributed data analysis and exploratory data analytics (EDA).  
It focuses on learning Spark DataFrames through hands-on exercises — from data loading to aggregations, joins, and genre-based insights.

---

## 🚀 Project Overview

The goal of this project is to perform **Exploratory Data Analysis (EDA)** on the MovieLens dataset using **Apache Spark**.  
You’ll learn how to efficiently manipulate and analyze large datasets using Spark transformations and actions.

### 🔹 Levels Covered:
1. **Load & Inspect Data** – Read and explore raw data, check schema, handle nulls.  
2. **Basic Aggregations** – Compute summary stats like average rating and count per movie.  
3. **Combine Data** – Join multiple datasets (movies + ratings) for deeper analysis.  
4. **Genre Analysis** – Reshape and analyze per-genre trends.

---

## 📂 Folder Structure

spark-movielens-eda/
│
├── data/ # Dataset files
│ ├── movies.csv
│ └── ratings.csv
│
├── notebooks/ # EDA notebooks
│ ├── 01_load_and_inspect.ipynb
│ ├── 02_basic_aggregations.ipynb
│ ├── 03_combine_data.ipynb
│ └── 04_genre_analysis.ipynb
│
├── README.md
└── .gitignore


---

## 🧰 Technologies Used

- **Apache Spark (PySpark)**
- **Python 3.10+**
- **Jupyter Notebook**
- **Pandas & Matplotlib** (for simple visualization)

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/dipikaspatil/data-engineering-projects.git
cd data-engineering-projects/spark-movielens-eda

### 2️⃣ Create a Virtual Environment
python3 -m venv venv
source venv/bin/activate       # Mac/Linux
# OR
venv\Scripts\activate          # Windows

### 3️⃣ Install Required Packages
pip install pyspark pandas matplotlib jupyter

### 4️⃣ Start Jupyter Notebook
jupyter notebook

Then open the notebooks/ folder and start from 01_load_and_inspect.ipynb.
