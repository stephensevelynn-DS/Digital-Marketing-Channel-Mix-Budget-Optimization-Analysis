# Digital-Marketing-Channel-Mix-Budget-Optimization-Analysis
Business Problem
Marketing teams routinely allocate budget based on historical habit rather than performance data — continuing to fund underperforming channels while underfunding those delivering the strongest returns. This project analyzes digital marketing spend across four channel categories to answer one critical question:

"Is budget being allocated where it performs best — and if not, what would the optimal allocation look like?"


Dataset

Source: Marketing Spend Dataset via Kaggle
Size: 308 campaign records across 11 channels
Channels: Social, Search, Influencer, Media
Metrics: Impressions, clicks, leads, orders, revenue, spend
Period: February 2021


Data Cleaning & Feature Engineering

Standardized inconsistent campaign naming conventions (e.g. facebOOK_tier2 → facebook_tier2)
Identified and flagged 19 zero-revenue campaign instances across 8 campaigns
Engineered four key performance metrics:

ROAS — Revenue per dollar spent
CPA — Cost per acquisition
CTR — Click through rate
Conversion Rate — Orders per click




Key Findings
1. Channel-Level ROAS
All four channels return above break even on average — but averages mask significant underperformers within each channel, making campaign-level analysis critical.
2. Campaign-Level Performance
CampaignROASVerdictyoutube_blogger4.07xStar performerfacebook_retargeting2.74xHighly efficientgoogle_hot1.91xSolidfacebook_lal0.13xCritical underperformergoogle_wide0.73xBelow break evenfacebook_tier20.76xBelow break even
facebook_lal is the single biggest budget drain — $2.6M spent returning only $300k. Poor performance persists regardless of spend level, suggesting a fundamental targeting misalignment rather than a budget sizing issue.
3. Budget Allocation vs Performance
ChannelCurrent ShareROASVerdictSocial45%0.86xOverfunded — losing moneyInfluencer27%2.54xUnderfunded — best performerMedia16%1.22xSlightly underfundedSearch11%1.07xUnderfunded
Nearly half of total budget flows to social channels returning below break even, while the highest performing channel — influencer — receives less than a third of budget.

Budget Reallocation Recommendation
Applied to a $1M total budget:
ChannelCurrentOptimalChangeInfluencer$271,000$446,000+$175,000Media$164,000$214,000+$50,000Search$113,000$188,000+$75,000Social$451,000$151,000-$300,000
Reallocating budget from underperforming social campaigns toward influencer and search channels has the potential to significantly improve overall ROAS without increasing total spend.

Tools Used

Python (Pandas, Matplotlib, Seaborn)
Jupyter Notebook
Kaggle


Why This Matters
In my work as a Fundraising Analyst I regularly advise clients on channel spend decisions — often challenging the instinct to cut high-performing channels like direct mail in favor of digital. The same principle applies here: budget should follow performance data, not assumptions. This project builds the analytical framework to make that case with numbers.

Project by Evelynn Stephens |https://www.linkedin.com/in/evelynn-stephens-datascience/| stephensevelynn@gmail.com
