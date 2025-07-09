Economic Sector Contribution Analysis

Project Description
This project focuses on analyzing economic sector contributions in Bahrain from 2011 to 2024. By evaluating time series data, we aim to provide insights into sector performance and contribute to informed decision-making aligned with Bahrain Vision 2030.

Problem Statement
Understanding the contributions of various economic sectors is crucial for policymakers to drive growth, diversify the economy, and enhance productivity. This project addresses the need for accurate forecasting and analysis of sector contributions to support strategic planning.

Dataset Description and Source
The dataset titled **"9-quarterly-contribu-kp-contrib.csv"** contains 1,288 observations representing the percentage contribution of various economic sectors over time. It includes data on:
- Year
- Quarter
- Sector (in both English and Arabic)
- Contribution %

The dataset is sourced from [Data.gov.bh](https://www.data.gov.bh/explore/dataset/9-quarterly-contribu-kp-contrib/information/).

Methodology Overview
1. Data Acquisition: Gather data from the government portal and clean it for analysis.
2. Exploratory Data Analysis (EDA): Visualize and summarize data to understand distributions and trends.
3. Time Series Forecasting: Implement ARIMA and SARIMA models to forecast future sector contributions.
4. Comparative Analysis: Compare contributions between public and private sectors to identify key drivers of economic performance.
5. Visualization: Develop interactive dashboards for stakeholders to explore sector contributions.

Key Findings and Insights
Private Sector Dominance: Sectors such as mining and manufacturing significantly outpace public sectors in contribution.
Utility Sector Importance: Essential services like electricity and water supply have notable contributions, indicating their role in economic stability.
Investment Opportunities: Identifying underperforming sectors like agriculture can guide future investments to diversify the economy.

Forecasting Instructions
At the end of the code, you can forecast contributions for any specific sector by replacing the name of the sector in the relevant section of the code. For example, to forecast contributions for the Manufacturing sector, locate the line that selects the sector data:

python
sector_data = df[df['sector (Constant Prices)'] == 'Manufacturing']['contribution %']
Change "Manufacturing" to the desired sector name (e.g., "Agriculture,forestry and fishing") to view the results for that sector. Run the subsequent forecasting and visualization code to analyze the predictions.
