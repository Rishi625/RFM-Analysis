# RFM-Analysis
# Data Set - https://www.kaggle.com/datasets/carrie1/ecommerce-data
This notebook demonstrates the process of performing RFM (Recency, Frequency, Monetary) analysis on customer data. RFM analysis is a marketing technique used to segment customers based on their purchasing behavior.

The notebook is structured as follows:

1. **Data Loading and Preprocessing**
   - Imports necessary libraries (pandas, numpy, matplotlib, seaborn)
   - Loads the dataset from a CSV file
   - Performs initial data exploration and cleaning

2. **RFM Metric Calculation**
   - Calculates Recency, Frequency, and Monetary values for each customer
   - Creates an RFM dataframe

3. **RFM Segmentation**
   - Segments customers into quartiles based on their RFM scores
   - Assigns RFM scores to each customer

4. **Customer Segmentation**
   - Defines customer segments based on RFM scores
   - Categorizes customers into segments like "Best Customers," "Lost Customers," etc.

5. **Visualization**
   - Creates various plots to visualize the RFM analysis results
   - Includes histograms, scatter plots, and heatmaps

6. **Insights and Recommendations**
   - Provides insights derived from the analysis
   - Offers recommendations for marketing strategies based on customer segments

## Usage

To use this notebook:

1. Ensure you have Jupyter Notebook or JupyterLab installed
2. Install required libraries: pandas, numpy, matplotlib, seaborn
3. Place your customer data CSV file in the same directory as the notebook
4. Update the file path in the notebook to match your CSV file name
5. Run the cells sequentially to perform the RFM analysis

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
