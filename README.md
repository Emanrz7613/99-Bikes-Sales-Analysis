# 99-Bikes-Sales-Analysis
99 Bikes Sales and Customer Segmentation Analysis

## Overview
This project analyzes sales data for **99 Bikes**, an Australian bike retailer. Using clustering and decision tree models, the project explores customer segmentation, sales trends, and factors contributing to customer profitability. The insights will help 99 Bikes optimize its marketing strategy, particularly for high-value customer groups.

## Dataset
The dataset includes customer demographics, transaction details, and sales data for 2017. Key features include:
- **Transaction Data**: Date, cost, product line, brand, and whether the order was placed online.
- **Customer Demographics**: Gender, age, job industry, and car ownership.
  

## Analysis Techniques
1. **Clustering Analysis**:  
   - Clustered customers based on demographic features and purchasing behavior. This helped identify different customer segments, such as online and in-store buyers.
2. **Decision Tree Analysis**:  
   - Built decision tree models to predict customer profitability based on demographic and transaction features.

## Models Used
1. **Clustering**:  
   Used K-means clustering to segment customers into different groups based on demographics, order type, and purchase frequency.
   - **Key Finding**: Certain customer groups, such as younger, online shoppers, showed higher profitability.
   
2. **Decision Tree**:  
   A decision tree model was used to classify customers into profit groups (low, medium, high) based on demographic and transaction data.
   - **Key Finding**: Age and tenure with the company were the most significant predictors of customer profitability.

## Key Insights
- **Seasonal Trends**: Identified peak sales periods for different bike types, helping 99 Bikes time promotions effectively.
- **Customer Segments**: The most profitable segments were younger, online buyers, and customers with a longer relationship with the brand.
- **Marketing Recommendations**: Focus marketing campaigns on high-value customer segments identified in the clustering analysis and optimize promotions around key sales periods.

## How to Run
1. **Clone the repository**:
    ```bash
    git clone https://github.com/Emanrz7613/99bikes-sales-analysis.git
    cd 99bikes-sales-analysis
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the notebooks**:
    - Use Jupyter Notebook to run the following:
      - `99Bikes_data_exploration.ipynb`: Explore the dataset.
      - `99Bikes_ClusterAnalysis.ipynb`: Perform customer clustering analysis.
      - `99Bikes_DecisionTree.ipynb`: Build decision tree models.

## Future Work
- Implement more advanced customer segmentation techniques.
- Expand the dataset to include more recent sales data.
- Apply additional machine learning models to improve profitability predictions.

## Contributors
This project was developed by:
- **Eric Chaves**
- **Gavin Ciganek**
- **Lara Kretschmer**
- **Joshua Nguyen**
- **Jessica Ricks**
