# ☕ Coffee Sales Analysis

A data analysis project exploring coffee shop sales transactions — uncovering best-selling products, revenue trends, peak hours, and payment behavior.

---

## 📁 Project Structure

```
coffee-sales-analysis/
│
├── index_1.csv                  # Raw sales dataset
├── coffee_sales_analysis.py     # Main analysis script
├── charts/                      # Auto-generated charts
│   ├── best_selling_coffee.png
│   ├── revenue_by_coffee.png
│   ├── payment_methods.png
│   └── sales_by_hour.png
└── README.md
```

---

## 📊 Dataset Overview

| Column | Description |
|---|---|
| `date` | Date of transaction |
| `datetime` | Exact timestamp |
| `cash_type` | Payment method (card / cash) |
| `card` | Anonymized card ID |
| `money` | Transaction amount |
| `coffee_name` | Product purchased |

- **3,636** total transactions
- **8** unique coffee products
- **97.6%** card payments, **2.4%** cash

---

## 🔍 Key Findings

- **Best Seller:** Americano with Milk (824 sales)
- **#2 Product:** Latte (782 sales)
- **Top Revenue:** Americano with Milk
- **Average Transaction:** ~31.75

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/coffee-sales-analysis.git
cd coffee-sales-analysis
```

2. Install dependencies:
```bash
pip install pandas matplotlib
```

3. Run the analysis:
```bash
python coffee_sales_analysis.py
```

Charts will be saved automatically in the `charts/` folder.

---

## 🛠️ Libraries Used

- `pandas` — data cleaning and analysis
- `matplotlib` — data visualization

