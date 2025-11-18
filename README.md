# 🍽️ Zomato Data Analysis Project

A complete exploratory data analysis (EDA) of Zomato restaurant data using Python.
This project helps understand cuisine trends, restaurant ratings, cost patterns, and customer preferences using real-world Zomato data.

---

## 📌 Project Overview

This project analyzes a Zomato dataset to uncover valuable insights such as:

* Rating distribution
* Impact of online ordering
* Popular restaurant types
* Cost analysis
* Location-wise trends
* Correlation between different features

The goal is to perform end-to-end data cleaning, preprocessing, visualization, and insight generation.

---

## 📊 Tech Stack

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**

---

## 📁 Dataset

The dataset includes:

* Restaurant name
* Location
* Rating
* Votes
* Approx cost
* Online ordering availability
* Cuisines

If the dataset is included in this repo, it will be inside `/data/`
Otherwise, please download it from Kaggle.

---

## 🧹 Data Cleaning Steps

* Remove duplicates
* Handle missing values
* Convert numerical columns to proper formats
* Clean "rate" column (remove `/5` etc.)
* Clean cost column (remove commas)

---

## 📈 Key Visualizations

* Rating distribution (histogram + KDE)
* Online vs Offline order rating comparison
* Restaurant type count plot
* Cost vs Rating scatter plot
* Heatmap (correlation between features)

---

## 🔍 Key Insights

* Online ordering restaurants tend to have slightly higher average ratings.
* Most restaurants fall under "Casual Dining" and “Quick Bites”.
* High-rated restaurants are concentrated in specific locations.
* Price and rating show weak correlation (customers pay for experience).

---

## ▶️ How to Run

1. Clone the repo

   ```bash
   git clone https://github.com/your-username/zomato-analysis.git
   cd zomato-analysis
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook

   ```bash
   jupyter notebook zomato-analysis-with-vishu.ipynb
   ```

---

## 📦 Folder Structure

```
📁 zomato-analysis
│── 📄 README.md
│── 📄 zomato-analysis-with-vishu.ipynb
│── 📁 data
│      └── zomato.csv
│── 📁 images (optional)
│── 📄 requirements.txt
```

---

## 🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to change.

