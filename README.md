# **A/B Testing Marketing Campaigns**

## 📌 *Project Overview*

This project evaluates the effectiveness of two digital marketing campaigns, Facebook Ads and Google AdWords—using A/B testing, regression analysis and time series. The objective is to determine which platform delivers higher engagement, conversions and overall cost-effectiveness, guiding smarter budget allocation.

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

- **Data Analysis**: Pandas, NumPy 

- **Visualization**: Matplotlib, Seaborn 

- **Modelling**: Scikit-learn (Regression), Statsmodels (Time Series)

- **Experimentation**: A/B testing framework

## 📈 *Approach*

1. **Data Cleaning & Preprocessing** – prepared and structured campaign data for analysis.

2. **Exploratory Data Analysis (EDA)** – examined views, clicks, conversions and costs to understand performance patterns.

3. **Visual Comparison** – compared Facebook vs AdWords across key KPIs including CTR, CPC and conversion rate.

4. **A/B Testing** – conducted statistical tests to measure significant differences between the two platforms.

5. **Regression Analysis** – built a linear regression model to predict conversions from ad clicks and evaluate predictive strength.

6. **Time Series Analysis** – analysed weekly and monthly conversion trends, identifying seasonality and cost fluctuations.

## 🔍 *Key Findings*

- Facebook Ad Performance

  - A Linear Regression model achieved an R² score of 76.35%, showing strong predictive power for forecasting conversions based on clicks.

  - Mondays and Tuesdays consistently showed the highest conversion rates, suggesting that early-week campaigns perform best.

  - Time series analysis revealed an overall upward trend in conversions across the year, with dips in February, April, May, June, August and November likely due to seasonal or behavioural shifts.

  - Cost per Conversion (CPC) analysis highlighted fluctuations across months, offering insights into the most cost-efficient periods for ad spend.

- AdWords vs Facebook

  - While both platforms generated steady engagement, Facebook proved to be more cost-effective in driving conversions.

  - AdWords, despite achieving reach and clicks, showed relatively lower ROI when compared to Facebook.

✅ Recommendations

- Prioritise Facebook Ads for budget allocation, especially targeting campaigns early in the week.

- Use regression analysis to forecast conversions from expected clicks and set realistic campaign goals.

- Apply time series forecasting to anticipate seasonal conversion patterns and adjust campaign intensity accordingly.

- Continue A/B testing with seasonal adjustments to validate long-term ROI patterns.

