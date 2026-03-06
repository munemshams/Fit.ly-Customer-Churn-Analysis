# Fit.ly Customer Churn Analysis

This project analyzes customer churn behavior for **Fit.ly**, a digital fitness platform offering subscription-based workout tracking and fitness content. The goal of this analysis is to identify behavioral patterns associated with churn and provide data-driven recommendations to improve customer retention.

The analysis integrates customer account information, user activity data, and customer support interactions to better understand how engagement and support experiences influence churn. The project was done using R Studio.

---

# Project Overview

Fit.ly operates under a subscription model with multiple plan tiers:

- Free
- Basic
- Pro
- Enterprise

Customer retention is critical for subscription-based businesses. High churn rates can reduce revenue growth and signal issues with user engagement or customer experience.

This project investigates:

- Who is churning
- Why customers churn
- What actions can reduce churn

The analysis identifies key behavioral signals linked to churn and provides actionable recommendations for improving retention.

---

# Data Source

The dataset used in this project is publicly available on Kaggle.

Dataset link:

https://www.kaggle.com/datasets/munemshariarshams/fit-ly-churn-analysis

The analysis uses three datasets:

### Account Information
- Customer ID
- Email
- State
- Plan
- Plan list price
- Churn status

### Customer Support
- Ticket timestamp
- Support channel
- Support topic
- Resolution time

### User Activity
- Event timestamps
- Event type (watch video, read article, track workout, share workout)

---

# Files Included

# Files Included

| File | Description |
|-----|-------------|
| `fitly_churn_analysis.Rmd` | R Markdown notebook containing the full data cleaning, feature engineering, and analysis workflow |
| `fitly_churn_analysis.html` | Knitted HTML output of the R Markdown analysis for easy viewing |
| `fitly_customer_churn_report.pdf` | Final written report summarizing the analysis, insights, and business recommendations |
| `fitly_customer_churn_report.docx` | Knitted word document output of the R Markdown analysis |
| `Fit.ly Customer Churn Analysis.pptx` | Presentation slides used for the project presentation |
| `Visuals` | A folder containing the generated visuals |
| `README.md` | Project documentation and overview |

# Video Presentation
The video presentation is hosted in this link below:
[https://cmich.webex.com/cmich/ldr.php?RCID=24104455395fd20fd40ece266af89d45](https://cmich.webex.com/recordingservice/sites/cmich/recording/9b9ef276c79b4028b1124eb644b32b42/playback)

## R Libraries Used

- tidyverse
- lubridate
- scales
