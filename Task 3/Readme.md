**Feature Engineering Task - README**

**Introduction:**
This repository contains the code and dataset for a feature engineering task focused on enhancing a CSV dataset provided by Estelle. The task involves transforming the data and creating new features to better understand price variations across different periods and months.

**Setup:**
To get started, download both the notebook and CSV provided in this repository. Run the cells within the notebook to set up the environment and load the dataset.

**Task Overview:**
- **Dataset:** Estelle has provided a CSV dataset to serve as the base for this task.
- **Initial Insights:** Estelle has shared insights on a feature related to price changes, sparking the beginning of our feature engineering journey.
- **Feature Creation:** 
  - **Average Price Changes:** One of the initial features engineered is the average price change by company between peak, mid-peak, and off-peak periods.
  - **Maximum Price Differences:** Another feature is created to highlight the maximum price difference across periods and months, offering an alternative perspective on price fluctuations.
- **Purpose:** These features aim to represent the variance of prices throughout the year, which can be valuable for consumers seeking better deals and understanding seasonal trends.

**Further Feature Engineering:**
- **Data Transformation:**
  - Conversion of date into months and removal of the raw date column.
  - Conversion of boolean columns into binary values.
  - Conversion of categorical columns into dummy variables.
- **Column Transformation:** 
  - Addressing skewed distributions by transforming columns using the logarithm function to achieve distributions closer to normal.

**Correlation Analysis:**
- **Identification of Redundant Columns:** 
  - Conducted correlation analysis to identify columns with high correlations.
  - Removal of redundant columns to streamline the dataset and enhance efficiency in subsequent analyses or modeling tasks.

**Conclusion:**
This feature engineering task provides valuable insights into price variations and enhances the dataset's suitability for further analysis and modeling. By incorporating these new features and transforming the data appropriately, we are better equipped to understand and predict trends in the dataset.