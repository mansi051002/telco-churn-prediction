# telco-churn-prediction
Predicting customer churn for a telecommunications company.

## Problem
The customer success team at a telecom company wants to reduce churn. This model predicts each customer’s probability of churning, so the team can rank customers by risk and offer retention discounts to those most likely to leave.
The two possible errors have very different costs: flagging a customer who would have stayed wastes a one-time discount, but missing a customer who actually churns loses all of their future revenue.
We therefore prioritise recall (catching as many churners as possible) while keeping precision reasonable, so the retention budget isn’t spent on customers who were never at risk.

## Setup

Requires **Python 3.14**.

```bash
git clone https://github.com/<your-username>/telco-churn-prediction.git
cd telco-churn-prediction
python3.14 -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

Then download the dataset as described in [`data/README.md`](data/README.md), and run `jupyter lab`.