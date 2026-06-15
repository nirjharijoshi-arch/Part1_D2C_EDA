# Business Memo

## Executive Summary

An exploratory analysis was conducted on 2,400 D2C customers to identify key drivers of customer churn. The overall churn rate in the dataset is **46.96%**, indicating that nearly half of customers are at risk of leaving within the next 60 days.

## Key Findings

### 1. Customer Inactivity is the Strongest Predictor of Churn

Recency (days since last purchase) shows a very strong relationship with churn:

| Recency Quartile | Churn Rate |
| ---------------- | ---------- |
| 0–25 days        | 9.75%      |
| 25–66 days       | 30.86%     |
| 66–129 days      | 58.71%     |
| 129–562 days     | 89.30%     |

Customers who have not purchased recently are dramatically more likely to churn.

### 2. Loyalty Tier Influences Retention

Churn rates differ across loyalty tiers:

| Loyalty Tier | Churn Rate |
| ------------ | ---------- |
| Silver       | 48.81%     |
| Gold         | 40.75%     |
| Platinum     | 37.14%     |

Silver-tier customers exhibit the highest churn risk and should be prioritized for retention initiatives.

### 3. Customer Engagement Appears Important

Preliminary analysis suggests that customers with lower levels of web activity and purchasing frequency are more likely to churn.

### 4. Customer Service Experience May Impact Churn

Support-ticket activity appears associated with churn and warrants further investigation to determine whether unresolved issues are contributing to customer attrition.

## Recommendations

1. Launch proactive retention campaigns targeting customers with high recency values.
2. Develop loyalty-program incentives focused on Silver-tier customers.
3. Monitor changes in purchase frequency as an early warning indicator.
4. Investigate customer-support interactions for potential service failures.
5. Build a predictive churn model to identify high-risk customers before they leave.

## Conclusion

The analysis indicates that customer inactivity is the strongest observable driver of churn. By focusing retention efforts on inactive and Silver-tier customers, the business can potentially reduce churn and improve customer lifetime value.
