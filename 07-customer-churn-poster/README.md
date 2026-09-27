# The Silent Exit: Predicting Customer Churn in the Malaysian Telecom Sector

**Course:** WQD7004 Programming for Data Science, Universiti Malaya  
**Type:** Individual academic poster  
**Tools:** R (ggplot2, dplyr, scales)  
**Format:** [High-resolution PDF](poster.pdf) · [JPG](poster.jpg)

![Poster](poster.jpg)

## Problem

Malaysian mobile customers can switch providers easily because switching costs are low, and identifying at-risk customers early is difficult. Keeping an existing customer is far cheaper than winning a new one, so losing them silently is expensive.

## Objective

Develop a predictive model that identifies customers likely to churn, to reduce attrition and protect revenue.

## Data

Monthly customer records from September 2019 and 2022, with 25 customer behaviour and service variables. The target is whether a customer is a potential churner. Source: Mustafa, Ling & Razak (2021), *Customer churn prediction for telecommunication industry: A Malaysian case study*, F1000Research 10:1274.

## Exploratory findings

| Finding | What the data shows |
|---|---|
| Churn trend | Churn fell slightly in 2020 but remains a major issue |
| NPS vs churn | Detractors have the highest churn in both years |
| Service duration vs churn | Longer service duration is associated with higher churn risk |
| ARPU vs churn | Churners contribute less revenue |

## Proposed solution: ChurnGuard AI

A retention dashboard mock-up built around the model:

- **Model logic:** data collection → AI prediction → risk classification → automated alert → action and intervention
- **Dashboard metrics:** at-risk customers, revenue at risk, actions taken and success rate
- **Customer details panel:** each customer's profile, risk factors and recommended actions
- **Priority action bar:** how many customers need contact now, today or this week

## Skills demonstrated

EDA and visualisation in R · churn problem framing · dashboard and product mock-up design · visual communication
