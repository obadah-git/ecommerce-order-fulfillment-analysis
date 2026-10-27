 E-Commerce Order Fulfillment Analysis

 Project overview
This project explores how order fulfillment performance relates to profitability in an e-commerce environment. It examines delivery time, return status, shipping cost, order value, and profit margin to identify operational patterns and possible areas for improvement.

 Business question
How can process improvements reduce delivery delays, product returns, and fulfillment costs while improving profitability in an e-commerce environment?

Dataset
The Kaggle public dataset with 34,500 order records and 17 variables. It includes order and customer identifiers, product category, price, discount, quantity, payment method, order date, delivery time, region, return status, total amount, shipping cost, profit margin, customer age, and customer gender.

Before publishing:** add the original dataset source URL and review its license/terms. Do not upload data unless redistribution is permitted.

 Tools
Python, Pandas, Matplotlib, Jupyter Notebook, descriptive statistics, and correlation analysis.

 Analysis workflow
1. Load the CSV into a Pandas DataFrame.
2. Inspect rows, data types, and summary statistics.
3. Check missing values and duplicate rows.
4. Calculate delivery, shipping, order-value, profit-margin, and return-rate summaries.
5. Explore correlations between numerical variables and profit margin.
6. Compare average delivery time across regions.
7. Interpret findings carefully and propose operational follow-up analyses.

 Findings reported in the original project
These figures are transcribed from the WGU report and should be reproduced by running the notebook against the original dataset before being presented as verified results:
- Records: 34,500
- Average delivery time: 4.81 days
- Average shipping cost: $6.15
- Average order amount: $170.01
- Average profit margin: $28.12 per order
- Return rate: 5.52%
- Correlation between total order amount and profit margin: approximately 0.893
- Correlation between shipping cost and profit margin: approximately 0.617
- Correlation between delivery time and profit margin: approximately 0.006
- The report states the East region had the longest average delivery time, approximately 6 days.

 Visualizations

 1. Average Delivery Time by Region
The East region had the longest average delivery time, at approximately 6 days. This may indicate an opportunity to investigate regional fulfillment processes.

2. Correlation with Profit Margin
Total order amount showed the strongest positive correlation with profit margin (approximately 0.893), while delivery time showed almost no linear correlation (approximately 0.006). Correlation does not establish causation.

3. Order Return Rate
Approximately 5.52% of orders were returned, while 94.48% were not returned.

 Recommendations from the report
- Investigate fulfillment processes in regions with longer delivery times.
- Monitor shipping costs and return rates.
- Explore order and product characteristics associated with profitability.
- Consider predictive modeling to identify orders at higher risk of return.

## Limitations
- The dataset is public and may not represent the operations of a particular e-commerce business.
- Correlation analysis describes association and does not prove causation.
- Findings must be checked against the original data and notebook outputs.

## Project status
Academic data analytics project developed as part of graduate studies in Data Analytics and Decision Process Engineering.

## Author
Obadah Elabhari
