# Walmart-Sales-Analysis-using-Python-Data-Analytics
This project performs an end-to-end **Walmart Sales Data Analysis** to understand sales performance, customer behavior, product trends, and business insights.

# 🛒 Walmart Sales Analysis using Python & Data Analytics

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Visualization](https://img.shields.io/badge/Data%20Visualization-Matplotlib%20%7C%20Seaborn-orange)
![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-red)

---

# 📌 Project Overview

This project performs an end-to-end **Walmart Sales Data Analysis** to understand sales performance, customer behavior, product trends, and business insights.

The project analyzes Walmart transaction data to identify important patterns related to:

- Sales trends
- Customer purchasing behavior
- Product performance
- Revenue contribution
- Branch and category performance

The analysis helps businesses make data-driven decisions for improving sales strategy and operational efficiency.

---

# 🎯 Objectives

The main objectives of this project are:

✅ Clean and preprocess Walmart sales data  
✅ Perform exploratory data analysis  
✅ Analyze sales and revenue patterns  
✅ Identify top-performing products/categories  
✅ Understand customer purchasing behavior  
✅ Generate business insights using visualization  

---

# 📊 Dataset Description

The dataset contains Walmart sales transaction details.

Important features:

| Feature | Description |
|-|-|
| Invoice ID | Unique transaction ID |
| Branch | Store branch |
| City | Store location |
| Customer Type | Customer category |
| Gender | Customer gender |
| Product Line | Product category |
| Unit Price | Product price |
| Quantity | Number of items purchased |
| Total | Total transaction amount |
| Date | Purchase date |
| Payment | Payment method |
| Rating | Customer rating |

---

# 🏗️ Data Analysis Workflow

```
Raw Walmart Dataset

        |

Data Cleaning

        |

Exploratory Data Analysis

        |

Feature Analysis

        |

Visualization

        |

Business Insights
```

---

# 🧹 Data Preprocessing

Performed data preparation:

## Missing Value Handling

Checked null values:

```python
df.isnull().sum()
```

Handled missing records where required.

---

## Data Type Conversion

Converted:

- Date columns
- Numerical features
- Categorical variables

into appropriate formats.

---

## Feature Engineering

Created additional features:

- Month
- Day
- Time period
- Revenue-based metrics

---

# 🔍 Exploratory Data Analysis

## Sales Analysis

Analyzed:

- Total sales
- Average sales
- Revenue trends
- Sales distribution


---

# 🏬 Branch Performance Analysis

Compared Walmart branches based on:

- Revenue
- Customer count
- Product performance


Identified:

- Best performing branch
- Sales contribution


---

# 🛍️ Product Category Analysis

Analyzed different product lines:

Examples:

- Electronics
- Food & Beverages
- Fashion accessories
- Home products


Insights:

- Highest selling categories
- Revenue contribution
- Customer preferences


---

# 👥 Customer Analysis

Studied:

## Customer Types

Compared:

- Members
- Normal customers


## Gender Analysis

Analyzed purchasing behavior by gender.

---

# 💳 Payment Analysis

Evaluated customer payment preferences:

- Cash
- Credit card
- E-wallet


---

# ⭐ Customer Rating Analysis

Analyzed customer satisfaction using ratings.

Insights:

- Average rating
- Category-wise ratings
- Customer satisfaction trends

---

# 📈 Visualizations Created

The project includes:

## Sales Distribution

- Bar charts
- Histograms


## Category Comparison

- Product line analysis


## Branch Comparison

- Branch-wise revenue


## Customer Insights

- Customer type analysis


## Correlation Analysis

Relationship between:

- Quantity
- Unit price
- Total sales
- Rating

---

# 🛠️ Technologies Used

## Programming

- Python


## Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn


## Environment

- Kaggle Notebook
- Jupyter Notebook


---

# 📂 Project Structure

```
Walmart-Sales-Analysis

│
├── walmart-project.ipynb
│
├── dataset
│   └── walmart_sales.csv
│
├── README.md
│
└── images

```

---

# 🚀 How to Run

Clone repository:

```bash
git clone https://github.com/AJITHPS7/Walmart-Sales-Analysis.git
```

Navigate:

```bash
cd Walmart-Sales-Analysis
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

Run:

```bash
jupyter notebook
```

Open:

```
walmart-project.ipynb
```

---

# 📌 Key Insights Generated

The analysis provides:

✅ Sales performance overview  
✅ Top-performing product categories  
✅ Branch-level comparison  
✅ Customer purchasing patterns  
✅ Payment method trends  
✅ Customer satisfaction analysis  

---

# 🔮 Future Improvements

Future enhancements:

🔹 Build sales forecasting model

🔹 Create interactive dashboard using Power BI / Streamlit

🔹 Predict future revenue

🔹 Add machine learning customer segmentation

🔹 Deploy analytics application

---

# 🎯 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Business Analytics
- Python Programming
- Data Interpretation


---

# 👨‍💻 Author

**Ajith P S**

MCA Graduate | Data Analyst | AI/ML Enthusiast

GitHub:
https://github.com/AJITHPS7


⭐ If you find this project useful, consider giving it a star!
