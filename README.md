# **A/B Testing Marketing Campaigns**

## 📌 *Project Overview*

This project evaluates the effectiveness of two digital marketing campaigns, Facebook Ads and Google AdWords—using A/B testing and statistical analysis. The objective is to determine which platform delivers higher engagement, conversions and overall cost-effectiveness, guiding smarter budget allocation.

## 🔍 *Research Question*

Which ad platform is more effective in terms of conversions, clicks and overall ROI?

## 📊 *Dataset*

The dataset contains 365 daily records of campaign data for both platforms, including:

- Date – campaign day

- Ad Views – impressions per platform

- Ad Clicks – user engagement

- Ad Conversions – successful outcomes

- Cost per Ad – spend per campaign

- CTR (Click-Through Rate) – clicks relative to views

- Conversion Rate – conversions relative to clicks

- CPC (Cost per Click) – cost efficiency

## 🛠️ *Tools & Libraries*

- Python

- Pandas, NumPy (data analysis)

- Matplotlib, Seaborn (visualisation)

- Statistical testing libraries for A/B analysis

## 📈 *Approach*

1. Data cleaning and preprocessing.

2. Exploratory data analysis (EDA) of campaign performance metrics.

3. Visual comparison of Facebook vs AdWords across views, clicks, conversions and spend.

4. A/B testing and statistical significance checks to determine the stronger performer.

## 🔍 *Key Findings*

- Facebook Ad Performance

  - A Linear Regression model achieved an R² score of 76.35%, showing strong predictive power for forecasting conversions based on clicks.

  - Mondays and Tuesdays consistently showed the highest conversion rates, suggesting that early-week campaigns perform best.

  -Over the year, conversions followed an upward trend, although dips were observed in February, April, May, June, August, and November, likely due to seasonal or     behavioural factors.

  - Cost per Conversion (CPC) analysis highlighted fluctuations across months, offering insights into the most cost-efficient periods for ad spend.

- AdWords vs Facebook

  -While both platforms generated steady engagement, Facebook proved to be more cost-effective in driving conversions.

  -AdWords, despite achieving reach and clicks, showed relatively lower ROI when compared to Facebook.

✅ Recommendations

- Prioritise Facebook Ads for budget allocation, especially targeting campaigns early in the week.

- Use predictive modelling on clicks-to-conversions to set realistic goals and optimise spend.

- Adjust campaign intensity in months with historically lower conversion rates to minimise wasted ad spend.

- Continue A/B testing with seasonal adjustments to validate long-term ROI patterns.

