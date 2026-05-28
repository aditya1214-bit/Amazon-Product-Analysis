# Product Data Analysis Project

A comprehensive data analysis project focused on understanding product pricing dynamics, customer satisfaction rating distributions, bestseller trends, and customer engagement metrics using Python's robust scientific stack.

---

## 📊 Visual Gallery Previews

### 1. Pricing Dynamics
* **Price Distribution**: Analyzing the concentration and density of product prices.
* **Average Price**: Visual comparison showing that Bestseller products maintain lower average pricing, reinforcing their market accessibility.
* **Price Boxplot Spread**: Spotlighting outliers, median boundaries, and price ranges based on bestseller status.

### 2. Rating & Review Trends
* **Rating Distributions**: Displaying high satisfaction profiles where most products rank between 4.0 and 4.8.
* **Top Reviewed Products**: Illustrating high review spikes dominated by specific consumer electronic and utility items.
* **Rating vs. Engagement (Scatter)**: Examining customer rating correlations with the volume of product reviews.

### 3. Correlation Heatmap
* A deep visual dive exposing numerical relationship indices between prices, customer ratings, and review sizes.

---

## 📁 Project Structure

```plaintext
product-data-analysis/
│
├── data/
│   └── cleaned_product_data.csv          # Standardized and cleaned data used for calculations
│
├── visuals/
│   ├── price_distribution.png            # Spread of product prices
│   ├── rating_distribution.png           # Frequency of customer star ratings
│   ├── bestseller_vs_nonbestseller.png   # Count of products by bestseller classification
│   ├── scatterplot_ratings.png           # Relationship between ratings and review count
│   ├── average_price.png                 # Mean price difference comparison
│   ├── heatmap.png                       # Core correlation indexes
│   ├── boxplot.png                       # Price quartile spread & outliers
│   └── top_reviewed_products.png         # Top 10 most reviewed products (truncated names)
│
├── report/
│   └── analysis_report.pdf               # Executive-level formatted business report
│
├── analysis.ipynb                        # Step-by-step interactive Jupyter EDA notebook
├── requirements.txt                      # Environment and package dependency list
└── README.md                             # Project overview and key results documentation
```

---

## 📈 Key Business Insights

1. **Strategic Pricing Advantages**: Bestseller products are generally lower-priced ($26.47 average) compared to non-bestsellers ($103.54 average). Lower-priced items are far more accessible and secure higher sales volumes.
2. **Customer Satisfaction Floor**: Most products maintain stellar ratings between 4.0 and 4.8 stars. Customer satisfaction does not correlate with price, implying customers expect premium performance irrespective of high or low prices.
3. **Engagement Disproportionality**: A few key products drive the bulk of review volume (e.g. cordless home phone setups, media streamers, and basic stationery accessories). Highly reviewed products are mostly standard daily utilities or popular gadgets.
4. **Weak Positive Rating-Volume Link**: Products with higher ratings (above 4.2 stars) show a slight positive trend in volume accumulation. However, price and star ratings show zero correlation, confirming pricing models do not influence subjective product satisfaction.

---

## 🚀 Execution Instructions

### Prerequisites
Ensure you have Python 3.10+ installed.

### Setup and Installation
1. Clone or copy the project files to your environment.
2. Navigate into the directory and install all required python packages:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Analysis
* Run the interactive Jupyter notebook `analysis.ipynb` through VSCode or JupyterLab.
* Alternatively, run the pipeline command:
   ```bash
   python generate_project.py
   ```
