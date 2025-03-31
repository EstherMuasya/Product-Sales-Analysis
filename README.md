# Product-Sales-Analysis
## Overview
This project analyzes sales data to determine the most effective sales method for revenue generation. 
## Dataset
The dataset includes:
- `week` → Week sale was made,counted as weeks since product launch
- `sales_method` → Character, which of the three sales methods were used for that customer
- `customer_id` → Character, unique identifier for the customer
- `nb_sold` → Numeric, number of new products sold
- `revenue` → Numeric, revenue from the sales, rounded to 2 decimal places.
- `years_as_customer` → Numeric, number of years customer has been buying from us
(company founded in 1984)
- `nb_site_visits` → Numeric, number of times the customer has visited our website in the last 6 months
- `state` → Character, location of the customer i.e. where orders are
 shipped

## Key Insights
- **`Email + Call` is the most effective sales method**, generating the highest revenue.
- **`Customer tenure` does not significantly impact revenue**, but site visits do.
- **`Revenue` trends remain stable over time**.

## Technologies Used
- **Python** (Pandas, Matplotlib, Seaborn)
- **Jupyter Notebook** for analysis

## How to Run the Project
1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/sales-analysis.git
2. **Install dependencies**
   
pip install pandas, matplotlib, seaborn

3. **Run the Jupyter Notebook**
 
jupyter notebook sales_analysis.ipynb

## Recommendations
- **Prioritize the Email + Call strategy** to maximize revenue.
- **Use data-driven insights** to refine customer segmentation.
- **Monitor site visits** to improve marketing efforts.
