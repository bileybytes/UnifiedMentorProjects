# Amazon Sales Data Analysis

## Introduction

This Jupyter Notebook provides a detailed analysis of Amazon Sales Data. Amazon, a global e-commerce leader, operates across numerous countries, offering a diverse range of products. Analyzing sales data is critical for understanding market trends, optimizing operations, and driving business growth. The dataset used in this analysis includes comprehensive records of transactions, with attributes such as region, country, item type, sales channel, order priority, order and ship dates, units sold, unit price, unit cost, total revenue, total cost, and total profit. The goal of this analysis is to explore sales trends, identify key metrics, and discover meaningful relationships among the data attributes, supporting Amazon's sales management and strategic decision-making processes.

## Data Overview

- **Dataset Name**: amazon_sales_data.csv
- **Number of Rows**: 100
- **Number of Columns**: 14
- **Data Types**: 
  - 7 Object columns
  - 2 Integer columns
  - 5 Float columns
- **Missing Values**: None

## Analysis Process

1. **Data Inspection**:
   - Verified dataset shape, checked for null values, and confirmed data types.

2. **Data Preprocessing**:
   - Removed the Order ID column.
   - Converted Order Date and Ship Date columns to datetime format.

3. **Feature Engineering**:
   - Added a 'Delivery Duration' column calculated as the difference between Ship Date and Order Date.
   - Extracted 'Year', 'Month', and 'Day' from the Order Date.

4. **Exploratory Data Analysis (EDA)**:
   - Conducted both Univariate and Multivariate Analysis.
   - Visualized data using various graphs and charts.

## Tools and Libraries

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Seaborn** and **Matplotlib**: For data visualization.

## Visualizations

The notebook includes a variety of visualizations such as bar charts, line graphs, histograms, and scatter plots, which help in understanding the data distribution, trends, and relationships.

## Conclusion

This notebook provides a comprehensive overview and analysis of Amazon Sales Data, offering insights into sales performance and trends. It serves as a useful resource for understanding the data and can be a basis for further analysis or business decision-making.

# Crop Production Data Analysis

## Introduction

The agriculture business domain, as a vital part of the overall supply chain, is expected to evolve significantly in the coming years through developments, particularly in the realm of the Future Internet. This analysis presents a novel Business-to-Business collaboration platform from the agri-food sector perspective, aiming to facilitate effective and flexible collaboration among numerous stakeholders from associated business domains. The dataset provides extensive information on crop production in India over several years. The ultimate goal of this analysis is to predict crop production and extract important insights, highlighting key indicators and metrics that influence crop production.

## Data Overview

- **Dataset Name**: Crop Production data.csv
- **Number of Rows**: 246,091
- **Number of Columns**: 7
- **Missing Values**: Present in the 'Production' column
- **Column Data Types**:
  - Object: 4 columns
  - Integer: 1 column
  - Float: 2 columns

## Analysis Process

1. **Data Inspection**:
   - Checked the shape of the dataset.
   - Identified null values and verified data types.

2. **Data Preprocessing**:
   - Filled the null values in numerical columns with mean values.
   - Created two new columns: 'Category of Area' and 'Production Category'.

3. **Data Analysis**:
   - Conducted Univariate, Bivariate, and Multivariate Analysis.

## Exploratory Data Analysis (EDA)

- **Tools and Libraries**:
  - **Pandas** and **NumPy**: For data manipulation and mathematical calculations.
  - **Seaborn** and **Matplotlib**: For creating graphs and charts.

- **Visualization Techniques**:
  - Multiple graphs and charts, including bar plots, histograms, scatter plots, and more, were created to explore and visualize the data.

## Note

All operations and analyses were conducted in Python using Jupyter Notebook.

