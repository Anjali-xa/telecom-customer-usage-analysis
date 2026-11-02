# Telecom Customer Usage KPI Guide

## KPI definitions
| KPI | Definition | Checks |
|---|---|---|
| Average revenue per user | Service revenue / average active subscribers | Align revenue period and subscriber denominator |
| Churn rate | Subscribers lost / subscribers eligible at period start | State voluntary/involuntary scope |
| Data usage per user | Total data volume / active users | Standardise MB/GB units |
| Average revenue per minute | Voice revenue / billed minutes | Exclude non-billable usage consistently |
| Complaint rate | Valid complaints / active subscribers | Deduplicate complaint IDs |

## Data validation
- Check unique customer and subscription identifiers.
- Standardise dates, billing periods, and usage units.
- Flag negative durations and impossible usage quantities.
- Distinguish inactive, suspended, and churned accounts.
- Reconcile billed usage against usage records where possible.
- Mask personal identifiers in published examples.

## Questions
1. How does usage vary by plan and customer segment?
2. Which cohorts have the highest churn?
3. Does usage differ between retained and churned customers?
4. How do complaints vary over time?

## Interpretation
Associations between usage, complaints, and churn are descriptive unless a suitable causal design is used.