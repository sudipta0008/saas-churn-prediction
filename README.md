# 🚀 SaaS Customer Churn Prediction

> Predicting customer churn using EDA, NLP Sentiment Analysis, 
> and Machine Learning with automated alert workflows

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Accuracy](https://img.shields.io/badge/Accuracy-83.9%25-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Project Overview
**TechFlow** is a fictional SaaS company experiencing customer churn. 
This project builds an end-to-end ML pipeline to predict which customers 
are likely to cancel — and automatically triggers retention workflows.

## 🎯 Results
| Metric | Value |
|--------|-------|
| Best Model | Logistic Regression |
| Test Accuracy | **83.9%** |
| Baseline | 65.8% |
| Improvement | +17.4 percentage points |
| At-Risk Customers Flagged | 672 out of 2,000 |

## 🔧 Tech Stack
- **Python** — pandas, scikit-learn, TextBlob, matplotlib, seaborn
- **NLP** — TextBlob sentiment analysis on support tickets
- **ML Models** — Logistic Regression, Random Forest, Gradient Boosting
- **Automation** — Email (SMTP), Slack Webhook, HubSpot CRM

## 📊 What Makes This Different
Most churn projects use recycled Telco datasets and stop at a prediction score.
This project:
1. Uses a **unique SaaS dataset** with free-text support tickets
2. Applies **NLP sentiment analysis** on customer support text
3. Fires **4 automated workflows** when a customer crosses a risk threshold
4. Sends **personalised retention emails** directly to at-risk customers

## 📧 Automated Workflows
When a customer's churn score crosses the threshold:
- 🔴 **HIGH risk** → CS team email + Slack alert + retention email to customer + CRM task
- 🟡 **MEDIUM risk** → Slack alert + retention email to customer

## 📚 References
This project addresses gaps identified in:
- Manzoor et al. (2024) *IEEE Access* — DOI: 10.1109/ACCESS.2024.3402092
- IEEE Xplore (2025) — DOI: 10.1109/ document 10968946
