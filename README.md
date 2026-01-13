# Subscription-Cohort-Analysis
This project performs subscription cohort analysis to assess conversion, retention, and churn, revealing strong retention among active users but weak early conversion due to early drop-off.


# Tech Stack
- Python
- pandas
- NumPy
- Tableau

# Data Source
The dataset is sourced from [Maven Analytics ](https://mavenanalytics.io/data-playground/streaming-video-subscriptions).

# Analysis Components
- **Churn Cohort Tables** (primary focus)
- **Trend Lines** for churn and retention over time
- **Box & Whisker Plot** showing median subscription tenure (months)
- **Pie Chart** illustrating the proportion of active vs inactive users

# Key Insights
- Churn rates increase as subscriber tenure progresses across cohorts.
- Active users remain subscribed for nearly twice the duration of churned users, indicating strong retention among engaged users.
- Overall conversion is weak due to significant early-stage churn.
- Churn-based cohorts provide clearer lifecycle insights than retention cohorts for this dataset.
- A historical anomaly shows near-100% churn driven by unsuccessful payments, which was resolved by July 2023.

## Interactive Dashboard
[View interactive Tableau dashboard](https://public.tableau.com/views/SubscriptionCohortAnalysis_17682845155300/Dashboard1)

<img width="1998" height="1598" alt="Dashboard 1" src="https://github.com/user-attachments/assets/183bd879-43c2-4be3-a504-8333d4f8fbdc" />

# License
This project is licensed under the MIT License.

Thank You!
