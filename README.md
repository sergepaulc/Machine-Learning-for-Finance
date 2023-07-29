# Machine-Learning-for-Finance

Machine learning models can be used in enterprise finance to streamline workflows, provide insights, help with decision making, and increase customer engagement.

Some basic statistical models can be implemented for multiple enterprise finance and accounting use cases such as:

- Computer vision techniques can be used to recognize characters and numbers, and extract data from a scanned document or an image
- Regressions can help to estimate the value of an asset
- Classifiers can be implemented to match and ranked transactions for bank reconciliation and 2/3-way matches, and predict account coding
- Anomaly and fraud detection systems can detect outliers for the general ledger, accounts payables, purchasing, expenses, and payroll
- Time series, sequence models, and generalized linear models can help with managing cash flows such as predicting if/when customers will be paying, predicting which vendor to pay first and when, insights to improve cash management, and forecasting of cash balances over time

Multiple models can be implemented together for an end-to-end workflow such as a complete solution to automate accounts payable:

- Extracting data for a scanned bill, accounts coding, detecting anomalies in the bill, paying the bill after the user validated it, and reconciling the payment of the bill with a bank debit transaction

More complex models can also be investigated:

- Recommender systems for recommending to the enterprise finance team, dashboards, reports, and tasks for an audit
- Reinforcement learning where transaction data is predicted, classified, anomalies are detected, and an agent will collect the feedback of the finance team to improve the model predictions

Last but not least, financial networks can be modeled as graph neural networks where financial entities can be represented as nodes, and their interconnections or interactions as edges. Graph neural networks (GNNs) can be used in finance for forecasting and anomaly detection:

- GNNs can help for product demand forecasting, supply chain management, and optimizing inventories
- GNNs are also good tools to evaluate risky financial transactions that could be illegal such as money laundering

This repository includes a few examples of models:

- Bank_reconciliation
- Matching_PO_to_Bills
- Outlier_detection_Bill
- Outlier_detection_PO
- Forecasting_cash_flows_ARIMA
- Forecasting_cash_flows_GAM
- Automating_account_payables


