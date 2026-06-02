# Digital-Marketing-Channel-Mix-Budget-Optimization-Analysis
## Business Problem
Marketing teams routinely allocate budget based on historical habit rather than performance data — continuing to fund underperforming channels while underfunding those delivering the strongest returns. This project analyzes digital marketing spend across four channel categories to answer one critical question:
 
> "Is budget being allocated where it performs best — and if not, what would the optimal allocation look like?"
 
---
 
## Dataset
- **Source:** Marketing Spend Dataset via Kaggle
- **Size:** 308 campaign records across 11 channels
- **Channels:** Social, Search, Influencer, Media
- **Metrics:** Impressions, clicks, leads, orders, revenue, spend
- **Period:** February 2021
 
---
 
## Data Cleaning & Feature Engineering
 
| Metric | Definition |
|---|---|
| ROAS | Revenue per dollar spent |
| CPA | Cost per acquisition |
| CTR | Click through rate |
| Conversion Rate | Orders per click |
 
---
 
## Campaign-Level ROAS
 
| Campaign | ROAS | Verdict |
|---|---|---|
| youtube_blogger | 4.07x | Star performer |
| facebook_retargeting | 2.74x | Highly efficient |
| google_hot | 1.91x | Solid |
| instagram_tier1 | 1.84x | Above break even |
| instagram_blogger | 1.33x | Above break even |
| banner_partner | 1.29x | Marginal |
| facebook_tier1 | 0.93x | Below break even |
| facebook_tier2 | 0.76x | Below break even |
| google_wide | 0.73x | Below break even |
| instagram_tier2 | 0.67x | Below break even |
| facebook_lal | 0.13x | Critical underperformer |
 
---
 
## Budget Allocation vs Performance
 
| Channel | Current Share | ROAS | Verdict |
|---|---|---|---|
| Social | 45% | 0.86x | Overfunded — losing money |
| Influencer | 27% | 2.54x | Underfunded — best performer |
| Media | 16% | 1.22x | Slightly underfunded |
| Search | 11% | 1.07x | Underfunded |
 
---
 
## Budget Reallocation Recommendation ($1M Total Budget)
 
| Channel | Current | Optimal | Change |
|---|---|---|---|
| Influencer | $271,000 | $446,000 | +$175,000 |
| Media | $164,000 | $214,000 | +$50,000 |
| Search | $113,000 | $188,000 | +$75,000 |
| Social | $451,000 | $151,000 | -$300,000 |
 
---
 
## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Kaggle
 
---
 
## Why This Matters
In my work as a Fundraising Analyst I regularly advise clients on channel spend decisions — often challenging the instinct to cut high-performing channels like direct mail in favor of digital. The same principle applies here: budget should follow performance data, not assumptions. This project builds the analytical framework to make that case with numbers.
 
---
*Project by Evelynn Stephens | [LinkedIn](https://www.linkedin.com/in/evelynn-stephens-datascience/) | stephensevelynn@gmail.com*

