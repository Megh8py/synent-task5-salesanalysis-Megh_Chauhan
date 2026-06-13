#  Task 5: Sales Data Analysis – Superstore Dataset

> Synent Technologies Data Science Internship

---

##  Problem Statement

Understanding business performance through data is critical for decision-making. This project analyzes the Superstore Sales Dataset to uncover monthly revenue trends, identify top-selling products, and evaluate profit across different categories and regions — delivering actionable business insights.

---

##  Dataset Details

| Property | Details |
|----------|---------|
| **Name** | Superstore Sales Dataset |
| **Source** | [Kaggle – Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) |
| **Rows** | ~9,994 |
| **Columns** | 21 |

### Key Columns
| Column | Description |
|--------|-------------|
| `Order Date` | Date the order was placed |
| `Sales` | Revenue generated per order |
| `Profit` | Profit earned per order |
| `Category` | Product category (Furniture, Office Supplies, Technology) |
| `Sub-Category` | Detailed product type |
| `Region` | Geographic region (East, West, Central, South) |
| `Segment` | Customer segment (Consumer, Corporate, Home Office) |
| `Quantity` | Number of units ordered |
| `Discount` | Discount applied |

---

##  Approach

### Step 1 – Data Loading & Exploration
- Loaded dataset and inspected shape, dtypes, and summary statistics
- Checked for missing values and duplicates

### Step 2 – Data Preprocessing
- Parsed `Order Date` as datetime
- Extracted `Year`, `Month`, `Month-Year` columns for time-based analysis
- Handled any missing or inconsistent values

### Step 3 – Monthly Revenue Trends
- Aggregated total sales by month
- Plotted line chart showing revenue trends over time
- Identified peak and low sales months

### Step 4 – Top-Selling Products & Categories
- Ranked sub-categories by total sales
- Compared performance across the 3 main categories
- Bar charts showing top 10 products by revenue

### Step 5 – Profit Analysis
- Analyzed profit margins by category and sub-category
- Identified most and least profitable segments
- Examined the impact of discounts on profit

### Step 6 – Regional & Segment Analysis
- Compared sales and profit across 4 regions
- Breakdown by customer segment (Consumer, Corporate, Home Office)

---

##  Results & Key Findings

- **Technology** had the highest total sales and profit margin among all categories
- **Furniture** generated high sales but had the lowest profit margin — heavily impacted by discounts
- **Q4 (Oct–Dec)** consistently showed peak sales — strong seasonal demand
- **The West region** outperformed other regions in both sales and profit
- **Tables and Bookcases** in Furniture were loss-making sub-categories
- **Phones and Chairs** were the top revenue-generating sub-categories
- High discounts (>40%) consistently led to negative profit margins

### Visualizations Generated
- Monthly revenue trend (line chart)
- Sales by category (bar chart)
- Top 10 sub-categories by sales (horizontal bar)
- Profit by sub-category (diverging bar chart)
- Regional sales comparison (bar chart)
- Discount vs Profit scatter plot

---

##  Repository Structure

```
synent-task5-salesanalysis-yourname/
│
├── task5_sales_analysis.ipynb     # Main notebook
├── Sample_Superstore.csv          # Raw dataset (or link below)
└── README.md                      # This file
```

---

## How to Run

1. Clone this repository
   ```bash
   git clone https://github.com/yourusername/synent-task5-salesanalysis-yourname.git
   ```
2. Install dependencies
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Open the notebook
   ```bash
   jupyter notebook task5_sales_analysis.ipynb
   ```
4. Run all cells top to bottom

---

## Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python 3.x | Programming language |
| Pandas | Data manipulation & aggregation |
| NumPy | Numerical operations |
| Matplotlib | Visualizations |
| Seaborn | Statistical visualizations |
| Jupyter Notebook | Development environment |

---

## 👤 Author

Megh Chauhan

Data Science Intern – Synent Technologies  
