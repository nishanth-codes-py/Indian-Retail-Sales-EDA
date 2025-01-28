# Indian-Retail-Sales-EDA


Overview
This project focuses on performing Exploratory Data Analysis (EDA) on a retail sales dataset from India. The objective is to derive actionable insights about sales, profit, customer behavior, and product performance, which can aid businesses in making data-driven decisions.

Objectives
Clean and preprocess the dataset by handling missing values and duplicates.
Perform in-depth exploratory data analysis (EDA) to uncover trends and patterns.
Visualize key insights to highlight business-critical metrics like sales, profit, and customer segmentation.
Optional: Use modeling to predict sales and analyze feature importance.

Dataset
The dataset used in this project is a synthetic Indian retail dataset containing:

Order Details: Order ID, Order Date, Region, and City.

Customer Details: Customer Segment.

Product Details: Product Category.

Sales Metrics: Sales, Profit, Quantity, and Discount.

Key Steps
1. Data Preprocessing
Checked for missing values and duplicates.
Imputed missing values using appropriate techniques.
Dropped duplicates to ensure data integrity.
Converted the Order Date column to a datetime format for time-based analysis.

2. Exploratory Data Analysis (EDA)
Descriptive statistics to summarize the dataset.
Visualizations to understand:
Regional and product-wise sales performance.
Profitability trends across customer segments and regions.
Correlation between sales, profit, discount, and quantity.
RFM (Recency, Frequency, Monetary) analysis for customer segmentation.

3. Insights
Identified the top-performing regions and cities based on sales and profit.
Analyzed the impact of discounts on profit margins.
Found seasonal trends in sales based on the Order Date.
Highlighted key product categories driving revenue and profit.

4. Predictive Modeling (Optional)
Built a simple Linear Regression model to predict sales based on the month.
Evaluated the model using Mean Absolute Error (MAE).
Technologies Used

Python Libraries:

pandas: Data manipulation and preprocessing.
numpy: Numerical computations.
matplotlib & seaborn: Data visualization.
scikit-learn: Predictive modeling and evaluation.
Jupyter Notebook: For interactive analysis.
How to Run the Project

Clone this repository:

Copy
Edit
git clone https://github.com/nishanth-codes-py/Indian-Retail-Sales-EDA.git
cd Indian-Retail-Sales-EDA

Install dependencies:
Copy
Edit
pip install -r requirements.txt

Run the Jupyter Notebook:
Copy
Edit
jupyter notebook
Explore the visualizations and results.
Results
Key findings are visualized through bar charts, heatmaps, and box plots.
RFM analysis segmented customers based on their purchasing behavior.
Sales prediction achieved an MAE of <insert value>.
Future Scope
Expand the dataset to include additional features like customer demographics.
Build advanced machine learning models for sales prediction.
Develop dashboards for real-time business monitoring.



Repository Structure

Copy
Edit
Indian-Retail-Sales-EDA/
│
├── data/
│   ├── indian_retailsales_data.csv        # Dataset
│
├── notebooks/
│   ├── sales_data_india.ipynb               # Jupyter Notebook for EDA
│
├── requirements.txt            # Python dependencies
├── README.md                   # Project documentation


Contributors
Nishanth M - Data Analyst & Project Owner
License
This project is licensed under the MIT License. Feel free to use, modify, and distribute.
