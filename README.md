# ChurnGuard

ChurnGuard is an explainable customer churn prediction dashboard for the IBM Telco Customer Churn dataset. It lets users adjust customer account, service, and billing details, then generates a churn risk score with SHAP-style feature explanations and retention action recommendations.

## Features

- Interactive customer churn prediction form
- Risk levels for low, medium, and high churn probability
- SHAP-style feature impact breakdown for each prediction
- Retention action recommendations based on customer risk factors
- Dataset insights for contract type, tenure, payment method, and internet service
- Model summary metrics including 75.8% accuracy and 0.843 AUC-ROC
- Responsive single-page HTML interface

## Tech Stack

- HTML
- CSS
- JavaScript
- Chart.js
- Google Fonts

## Dataset

The dashboard is based on the IBM Telco Customer Churn dataset with 7,043 customers. It includes account information, contract type, tenure, monthly charges, billing method, service usage, and churn outcomes.

## How to Run

Open `churngaurd-2.html` in any modern web browser.

No installation or build step is required.

## Project Structure

```text
.
├── churngaurd-2.html
└── README.md
```

## Notes

This project presents an interactive frontend simulation using churn metrics, feature importances, and retention recommendations from an XGBoost and SHAP-based churn analysis workflow.
