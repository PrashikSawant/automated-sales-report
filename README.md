# 📊 Automated Sales Report Generator

Automated Python pipeline that reads raw Superstore sales data and generates 
a formatted, multi-sheet Excel report with key business KPIs.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)
![openpyxl](https://img.shields.io/badge/openpyxl-Latest-orange.svg)
![Excel](https://img.shields.io/badge/Microsoft_Excel-Output-217346.svg)

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [KPIs Generated](#kpis-generated)
- [Installation](#installation)
- [Usage](#usage)
- [Output](#output)
- [Business Impact](#business-impact)
- [Technologies Used](#technologies-used)
- [Contact](#contact)

---

## 🎯 Project Overview

This project automates the process of transforming raw sales CSV data into 
a clean, formatted Excel report — eliminating hours of manual work.

### 🏆 Key Highlights
- **9,800 rows** of sales data processed automatically
- **5 KPI sheets** generated in one click
- **$2.26M+** Total Revenue analyzed
- **Zero manual effort** after initial setup

---

## 📊 Dataset

**Source**: Superstore Sales Dataset (Kaggle)  
**Size**: 9,800 rows × 18 columns  
**Period**: 2015 – 2018

| Column | Description |
|--------|-------------|
| Order Date | Date the order was placed |
| Sales | Revenue from the order |
| Region | Geographic region of the sale |
| Category | Product category |
| Product Name | Name of the product sold |

---

## 📈 KPIs Generated

| KPI | Sheet Name | Description |
|-----|------------|-------------|
| 💰 Total Revenue | Summary | Overall revenue across all years |
| 📍 Revenue by Region | Region Sales | Sales breakdown by East/West/Central/South |
| 🏆 Top 5 Products | Top Products | Highest revenue generating products |
| 📅 Monthly Trend | Monthly Sales | Month-by-month revenue trend |
| 📦 Category Sales | Category Sales | Revenue split by Furniture/Office/Technology |

---

## 🚀 Installation

### Prerequisites
```
Python 3.8+
Jupyter Notebook
```

### Setup
```bash
# Clone the repository
git clone https://github.com/PrashikSawant/automated-sales-report.git
cd automated-sales-report

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook sales_report.ipynb
```

---

## 💡 Usage

1. Place your `train.csv` file in the project folder
2. Open `sales_report.ipynb` in Jupyter
3. Run all cells in order
4. Find your `Sales_Report.xlsx` generated automatically in the same folder

---

## 📤 Output

The script generates **`Sales_Report.xlsx`** with 5 formatted sheets:

| Sheet | Content |
|-------|---------|
| Summary | Total Revenue KPI |
| Region Sales | Revenue by 4 regions |
| Top Products | Top 5 products by revenue |
| Monthly Sales | Month-wise revenue trend |
| Category Sales | Revenue by product category |

### Sample Results

| KPI | Value |
|-----|-------|
| 💰 Total Revenue | $2,261,536.78 |
| 🏆 Top Product | Canon imageCLASS 2200 ($61,599) |
| 📦 Best Category | Technology ($827,455) |
| 📍 Best Region | West ($710,219) |

---

## 📈 Business Impact

| Metric | Before | After |
|--------|--------|-------|
| Report Generation Time | 2-3 hours manually | Under 30 seconds |
| Human Errors | Frequent | Zero |
| Sheets Produced | 1 basic sheet | 5 formatted KPI sheets |
| Reusability | None | Works on any similar CSV |

---

## 🛠 Technologies Used

| Tool | Purpose |
|------|---------|
| Python 3.8+ | Core programming language |
| Pandas | Data loading, cleaning, KPI calculation |
| openpyxl | Excel file creation and formatting |
| Jupyter Notebook | Interactive development environment |

---

## 📞 Contact

**Prashik Sawant** - Data Analyst

- 📧 Email: prashiksawant47@gmail.com
- 💼 LinkedIn: [Connect with me](https://www.linkedin.com/in/prashik-sawant-ds)
- 🌐 Portfolio: https://prashiksawant.github.io/Portfolio/
- 🐙 GitHub: https://github.com/PrashikSawant

---

⭐ If this project helped you, please star the repository!

*Turning Raw Data into Business Insights Automatically* 💡
```

---

### How to Update on GitHub:
1. Go to your **`automated-sales-report`** repo
2. Click on **`README.md`**
3. Click the **pencil icon** to edit
4. **Select all** and delete everything
5. Paste the new README above
6. Click **"Commit changes"**

---

Also create a **`requirements.txt`** file in the same repo by clicking **"Add file" → "Create new file"**, name it `requirements.txt` and paste this:
```
pandas
openpyxl
jupyter
