# A/B Test Analysis

In this project, we analyze the results of an A/B test conducted by a client. The test compared two ad campaigns: a control group that saw the current campaign using the usual bidding strategy, and a test group that saw a new campaign with a different bidding method. The objective is to analyze key metrics such as Click-Through Rate (CTR), Conversion Rate (CR), and Cost Per Acquisition (CPA) to evaluate the effectiveness of the test campaign.

## Project Structure

1. **Data Loading**: The datasets for the test and control groups are loaded, cleaned, and combined into a single dataframe for further analysis.
2. **Data Cleaning**: Missing data is identified and handled by ignoring any incomplete observations.
3. **Exploratory Data Analysis (EDA)**: Various visualizations are created to compare key metrics like spend, clicks, and purchases over time.
4. **Statistical Testing**: A t-test is performed to determine if there are significant differences between the control and test groups in terms of CTR and Conversion Rate.

## Steps Involved

### 1. Data Preparation
The data from both the **Test** and **Control** campaigns are combined into a single dataframe for further analysis.

### 2. Exploratory Data Analysis
Key metrics such as **spend**, **clicks**, and **purchases** are visualized over time. These visualizations help in understanding the overall trend of the campaigns and comparing their performance.

### 3. Key Metric Calculations
Important performance metrics are calculated, including:
- **CTR (Click-Through Rate)**: The percentage of people who clicked on an ad after seeing it.
- **CR (Conversion Rate)**: The percentage of users who made a purchase after clicking an ad.
- **CPA (Cost Per Acquisition)**: The cost of acquiring one customer or making one purchase.

### 4. Statistical Testing: T-Test
A t-test is performed to determine if there is a statistically significant difference between the **CTR** and **Conversion Rate** of the **Test** and **Control** campaigns.

### 5. Results
- **CTR Analysis**: The Test campaign has a significantly higher CTR, indicating its effectiveness in generating clicks.
- **Conversion Rate Analysis**: There is no statistically significant difference in Conversion Rate, suggesting that both campaigns performed similarly in terms of converting clicks into purchases.

## Conclusion

- **CTR**: The Test campaign significantly outperformed the Control campaign in terms of Click-Through Rate, suggesting that the new bidding strategy was more effective at generating clicks.
- **Conversion Rate**: No significant difference was found in Conversion Rate, meaning both campaigns performed similarly in terms of converting clicks into purchases. 

This analysis provides valuable insights for future campaigns, especially in refining bidding strategies to improve engagement.
