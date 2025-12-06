# Global Fashion Market Analysis

## Project Overview  
Exploratory analysis and a simple next-month sales forecast on a simulated e-commerce dataset covering January–August 2022. The project highlights top products, product type distribution, payment preferences, country performance, and a one-step linear forecast.

Key questions:
- Which products and product types sold the most?  
- How did monthly sales change over time?  
- Which countries contributed most to revenue?  
- Which payment methods were most commonly used?  
- What is a simple forecast for next month’s total sales?

---

## Data
The dataset is licensed under **Apache 2.0** and sourced from Kaggle (simulated sneaker & streetwear sales, Jan–Aug 2022).
- Includes 500 clean, non-null, and unique transaction records. It covers sales from several countries and over 30 product names.
- Full dataset is included in the repo for reproducibility.  
- Attribution: Kaggle dataset `https://www.kaggle.com/datasets/atharvasoundankar/sneakers-and-streetwear-sales-2022`

Key fields include:

- `Date` – date of the transaction

- `Country` – country of purchase

- `Gender` – customer gender

- `Product and Category` – product details

- `Quantity Sold` – number of units sold per transaction

- `Unit Price and total Amount` – pricing and revenue details

- `Payment Mode` – method used for payment

---

## Figures
![Top products](figures/top_products.png)
![Product type sales distribution](figures/product_type_distribution.png)
![Sales by country](figures/country_sales.png)
![Next month sales forecast](figures/next_month_forecast.png)

---

## How to run
1. Clone the repo:
   ```bash
   git clone https://github.com/PKTrance/Global-Fashion-Market-Analysis.git
   cd Global-Fashion-Market-Analysis
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Open the notebook:
   ```bash
   jupyter notebook sneaker-streetwear-sales-analysis.ipynb

---

## Files
- `sneaker-streetwear-sales-analysis.ipynb` — full Jupyter notebook with code, visuals, and commentary.  
- `sneakers_streetwear_sales_data.csv` — the dataset used for analysis (Apache 2.0 license).  
- `requirements.txt` — Python packages used.  
- `figures/` — exported PNGs used in the README.

---

## Notes

The notebook is organized into: Introduction, Data Overview, EDA (product/category/country/payment), Key Insights, and Forecasting.

The forecast uses a simple linear regression as a demonstration of predictive thinking given limited history. 

## Contact

Patrick Tran — `https://www.linkedin.com/in/patricktran22/` — patricktran@g.ucla.edu
