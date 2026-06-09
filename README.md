# Nigeria-Financial-Crime-Intelligence-&-AML-Risk-Monitoring-Platform
Power BI portfolio project for fraud detection, AML risk monitoring, and financial crime investigation using Nigerian transaction data.

Overview
This project shows how data analytics and visualization can strengthen fraud detection, AML risk monitoring, and investigation prioritization within the Nigerian payments ecosystem. Using the publicly available NIBSS Fraud Dataset, an end to end Financial Crime Intelligence & AML Monitoring Platform was built in Power BI to highlight fraud trends, risk concentration across NIP/POS/USSD channels, customer exposure, and high risk transactional activity.
________________________________________
Tools Used
•	Power BI
•	Power Query
•	DAX
•	Star Schema Data Modelling
________________________________________
Dataset
•	Source: Kaggle – NIBSS Fraud Dataset
•	Approximately one million transaction records
•	Country: Nigeria
________________________________________
Risk Scoring Methodology
The project implements a rule-based risk scoring framework based on four risk components:
•	Amount Risk Score
•	Channel Risk Score
•	Geographic Risk Score
•	Frequency Risk Score
Overall Risk Score =
Amount Risk Score + Channel Risk Score + Geographic Risk Score + Frequency Risk Score
Transactions were subsequently classified into the following risk bands:
•	High
•	Medium-High
•	Medium
•	Medium-Low
________________________________________
Dashboard Pages
Nigerian Financial Crime Dashboard
Provides a high level view of fraud activity, transaction volumes, channel exposure (NIP, POS, USSD, Mobile, Web), and geographic hotspots across Nigeria.
Nigeria AML Risk Monitoring Dashboard
Supports risk based monitoring by highlighting high risk customers, payment channels, merchant categories, and locations that may require enhanced due diligence.
Nigerian Financial Crime Investigation Dashboard
Enables investigation prioritization through structured queues, analysis of fraud techniques, and monitoring of high risk or suspicious activity.
________________________________________
Dashboard Screenshots
Executive Financial Crime Dashboard
Nigeria AML Risk Monitoring Dashboard
Financial Crime Investigation Dashboard
________________________________________
Key Findings
•	Fraud activity concentrated in specific channels — Most confirmed cases were linked to a small set of high risk NIBSS channels and merchant categories.
•	Risk uneven across locations — Certain states showed disproportionately higher exposure compared to the rest of the country.
•	Only a small share required urgent review — A limited portion of total transactions triggered high risk flags or required immediate analyst attention.
•	High risk behaviour concentrated among few customers — Suspicious activity was not widespread but clustered around a small group of customers.
•	Social engineering dominated confirmed fraud — Techniques such as impersonation, phishing, and account takeover accounted for most verified fraud incidents.
________________________________________
Recommendations
•	Strengthen monitoring of high risk transactions — Prioritise unusual or high value activity, especially across NIP, POS, and USSD channels.
•	Tighten controls around higher risk channels and MCCs — Apply additional checks and preventive rules for channels and merchant categories with elevated fraud exposure.
•	Adopt risk based investigation workflows — Focus analyst effort on customers, merchants, and locations with the highest risk signals.
•	Review and recalibrate risk scoring models — Continuously adjust scoring thresholds to reflect emerging fraud patterns and behavioral shifts.
•	Leverage analytics to enhance fraud and AML monitoring — Expand the use of dashboards, trend analysis, and behavioural insights to improve detection and decision making.
________________________________________
Dataset Limitations
This project uses a publicly available dataset and is intended strictly for learning and portfolio demonstration. As such, the insights do not represent real Nigerian banks or NIBSS participants, nor do they reflect actual customers, transactions, or confirmed criminal activity. The results should be viewed as illustrative rather than operational.
________________________________________
Documentation
A full report covering the business problem, objectives, dataset details, data model, risk scoring approach, key findings, recommendations, limitations, and conclusions is included in the project’s documentation folder.
________________________________________
Disclaimer
This project contains no confidential customer, institutional, or regulatory information. All work was created solely for educational and portfolio purposes using publicly available data

