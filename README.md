# NUS SDS Datathon 2025 - Financial Advisor Matching System

## Overview
In this project, we developed a data-driven system to match financial advisors with potential clients by analyzing patterns in successful advisor-client relationships. Our dataset consists of **20,000 customers** and **10,000 advisors**, and our goal was to build a recommendation system that optimally pairs clients with advisors.

### Key Insights:
- **Female advisors** exhibit **higher retention rates** with female clients.
- **Younger clients** strongly prefer **digital-first financial products**.
- **Experienced advisors** excel with **high-value clients**, prioritizing quality over quantity.

## Methodology

### 1. Data Preparation
- Cleaned and preprocessed the dataset.
- Standardized categorical variables such as age groups, experience levels, and product preferences.
- Extracted features such as **past sales history**, **client demographics**, and **interaction frequency**.

### 2. Recommendation Model
- Implemented a **collaborative filtering approach** to suggest advisor-client matches.
- Integrated **machine learning models** to predict compatibility based on:
  - Prior engagement success rates.
  - Demographic and behavioral data.
  - Sales performance history.
- Evaluated performance using **precision, recall, and F1-score**.

## Requirements
To set up the environment, install dependencies from `requirements.txt`:
```bash
pip install -r requirements.txt
```

## Execution Steps
1. **Set up the environment** by running the first cell in the notebook to install dependencies.
2. **Run all notebook cells** in sequential order.
3. **Analyze outputs** to interpret recommendations and insights.

## Limitations
- ❗ **Human factors** such as personal rapport and communication styles are difficult to quantify.
- ⚠️ **Data availability** may impact model performance, as real-world preferences are nuanced.

## Conclusion
This recommendation system provides a structured approach to matching financial advisors with clients based on **data-driven insights**. While the system shows promising results in identifying compatible matches, it highlights the importance of **both quantitative and qualitative** factors in financial advisory relationships.
