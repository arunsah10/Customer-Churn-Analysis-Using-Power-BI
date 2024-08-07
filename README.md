
# Customer Churn Analysis
## Project Overview

The **Customer Churn Analysis** project aims to analyze and predict customer churn in telecom datasets. This project utilizes SQL Server for ETL processes and data cleaning, Power BI for data visualization and analysis, and Python (specifically Random Forest) for building and evaluating a machine learning model. The Random Forest model achieved an accuracy of 85%, providing valuable insights into customer behavior and predicting future churn.

## Files Included

- **`Churn Prediction.ipynb`**: Jupyter Notebook containing the Random Forest model for predicting customer churn.
- **`Churn Analysis - Prediction.png`**: Power BI analysis of future churn predictions.
- **`Churn Analysis - Summary.png`**: Power BI summary of churn data.
- **`Churn Analysis.pbix`**: Power BI file with detailed data analysis and visualizations.
- **`Churn Analysis.pdf`**: PDF file containing images and summaries of Power BI analysis.
- **`Churn Reasons.png`**: Power BI analysis of churn reasons.
- **`Customer_Data.csv`**: Original dataset used for analysis.
- **`Predicted.csv`**: Contains the results of churn predictions.
- **`Prediction Data.xlsx`**: Data used for predicting future churns.

## Project Description

### Problem Statement

Customer churn is a significant issue for telecom companies, affecting their profitability and growth. This project focuses on predicting which customers are likely to churn using historical data. By analyzing customer behavior and patterns, we can identify high-risk customers and develop strategies to retain them.

### Application

1. **ETL Process in SQL Server**: Extract, transform, and load data from various sources to prepare it for analysis.
2. **Data Cleaning in SQL Server**: Clean and preprocess the data to ensure accuracy and completeness.
3. **Power BI Transformations**: Apply data transformations in Power BI to prepare for visual analysis.
4. **Power BI Visualization & Enhancing Visuals**: Create interactive dashboards and reports to visualize churn patterns and trends.
5. **Build Machine Learning Model**: Develop and evaluate a Random Forest model in Jupyter Notebook to predict customer churn.
6. **Visualize Predicted Data in Power BI**: Integrate predicted churn data into Power BI for comprehensive analysis and reporting.

### Advantages

- **Improved Customer Retention**: Identify high-risk customers and implement targeted retention strategies.
- **Data-Driven Decision Making**: Utilize predictive analytics to make informed business decisions.
- **Enhanced Visual Insights**: Leverage Power BI for interactive and insightful visualizations of churn data.

## How to Use the Power BI File

1. **Download Power BI Desktop**: Ensure you have Power BI Desktop installed. [Download Power BI Desktop](https://powerbi.microsoft.com/desktop/).

2. **Open the Power BI File**:
   - Launch Power BI Desktop.
   - Go to `File` > `Open` and select the `Churn Analysis.pbix` file from your local setup.

3. **View and Analyze Data**:
   - Explore various reports and dashboards created in Power BI.
   - Review the visualizations in `Churn Analysis - Prediction.png`, `Churn Analysis - Summary.png`, and `Churn Reasons.png`.

4. **Interact with the Data**:
   - Use filters and slicers to interact with the data and gain insights into customer churn.

## How to Run the Jupyter Notebook

1. **Install Dependencies**: Ensure you have the necessary libraries installed. You can install them using `pip`:
   ```bash
   pip install pandas scikit-learn matplotlib
   ```

2. **Run the Notebook**:
   - Open a command prompt or terminal.
   - Navigate to the directory containing `Churn Prediction.ipynb`.
   - Run the following command to start Jupyter Notebook:
     ```bash
     jupyter notebook Churn Prediction.ipynb
     ```

3. **Execute the Cells**: Open the notebook in your browser and execute each cell to run the Random Forest model and analyze the results.

## Conclusion

This project demonstrates a comprehensive approach to customer churn analysis using a combination of SQL Server, Power BI, and Python. By leveraging these tools, you can effectively predict and analyze customer churn, enabling better decision-making and improved customer retention strategies.


**Author:** Arun Kumar Sah  
**Copyright:** © 2024 Arun Kumar Sah  
**GitHub Repository:** [Your GitHub Repo Link](https://github.com/arunsah10/Customer-Churn-Analysis-Using-Power-BI)
