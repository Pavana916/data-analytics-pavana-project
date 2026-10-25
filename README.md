
# 📊 Data Analytics Project

### Suspicious & Potentially Fraudulent Credit-Card Transaction Analysis

*A Power BI dashboard for exploring transaction activity and identifying
fraud patterns.*
:::📌 Overview
The Data Analytics Project is an interactive Power BI report focused
on suspicious and potentially fraudulent credit-card transactions. It
helps users review transaction volumes, monitor fraud indicators, and
explore patterns across transaction hours, statuses, and amount bands.
📈 Dashboard Highlights
  KPI / Visual                        Description
  Total Transactions              Overall count of transactions in
                                      the report.

  Fraud Transactions              Count of transactions classified as
                                      fraudulent.

  Fraud Rate (%)                  Percentage of transactions
                                      identified as fraudulent.

  Fraud Amount                    Amount associated with transactions
                                      classified as fraudulent.

  Fraud by Transaction Hour       Column chart for exploring how
                                      fraud activity varies by hour.

  Transactions by Status          Donut chart showing transaction
                                      distribution by status.

  Interactive Filters             Slicers for transaction hour,
                                      transaction status, and amount
                                  band.
🛠️ Technology Stack
- Microsoft Power BI Desktop
- Power BI data model
- DAX measures, as defined in the report
📁 Project File
The repository contains the Power BI report:

data analytics pavana project.pbix

The .pbix file contains the report visuals and its embedded Power BI
model. Because the file exceeds GitHub's regular 100 MB file limit,
it is stored using Git Large File Storage (Git LFS).
🚀 How to Open the Report
Option 1: Clone with Git
Make sure Git and Git
LFS are installed, then run:
git lfs install
git clone https://github.com/Pavana916/data-analytics-pavana-project.git
cd data-analytics-pavana-project
git lfs pull
Open data analytics pavana project.pbix using Microsoft Power BI
Desktop.
Option 2: Download from GitHub
1. Clone the repository using the commands above, or download the
   repository if Git LFS is configured to retrieve the full report.
2. Open the .pbix file in Power BI Desktop.
3. Use the available slicers to explore the dashboard.
Troubleshooting: If the downloaded .pbix file appears unusually
small or will not open, install Git LFS and run git lfs pull from
inside the repository folder.

🗂️ Repository Structure
data-analytics-pavana-project/
├── data analytics pavana project.pbix
├── .gitattributes
└── README.md
📝 Notes & Limitations
- The supplied ZIP contained the .pbix report only. No separate
  dataset, source-code files, or data dictionary were included.
- The dataset source and exact business definitions used for the fraud
  measures are not documented here.
- Review the Power BI model and measure definitions before using the
  report for operational or financial decisions.
👤 Author
Pavana916
- GitHub: @Pavana916
- Repository:
  data-analytics-pavana-project

**Built with Microsoft Power BI**
