# A/B Testing for Landing Page Designs

## 📋 Project Overview
This project involves conducting an A/B test to compare three landing page designs - Vibrant, Heat, Cold - and determine which design performs better in terms of conversion rates. Beyond that, the analysis will consider other factors such as demographic and user behaviours. The insight will enhance marketing strategies, improve customer experience on the web/app, and boost speaker sales.

## ❓Business Questions
Analysis and A/B testing try to answers business questions as follows.
1. Which design is more effective in converting into sign-up or purchase as well as improve customer engagement (duration and page views)?
2. Which channel contributes the most to the number of sessions and conversion?
3. When is the peak customer traffic on our website/app?
4. Which customer segments contribute the most to total sales and conversion rates?

## 📊 Dataset Overview
Dataset for this project was downloaded from [Kaggle](https://www.kaggle.com/datasets/sandeep1080/bassburst/data). This dataset contains website conversion data for bluetooth speaker sales with a total of 30,000 user sessions. The sessions are segmented by the landing page variant each user saw. The dataset also includes user-specific details, session engagement, product purchases, and payment methods, providing a comprehensive view of how website features and user characteristics influence conversions. 
| Column Name | Description |
|------|------|
| `user_id` | Unique identifier for each visitor  |
| `session_id` | Unique identifier for each session or visit   |
| `sign_in` |  Indicates if the user logged in via email or used guest access |
| `name` | Name of the visitor (generated from multiple locales)   |
| `demographic_age` | Age of the visitor (ranging from 14 to 80)   |
| `demographic_age_group` | Age group of the visitor: "Teenage", "Adult", "Old"   |
| `demographic_gender` | Gender of the visitor (Male, Female, Not Answered)  |
| `email` |  Email address of the user (if logged in via email)  |
| `location` | The city where the visitor is located   |
| `country` | Country corresponding to the location   |
| `device_type` | Type of device used (Mobile, Desktop, Tablet)   |
| `timestamp` | Session start time   |
| `variant_group` | The landing page design variant the user saw (Vibrant, Cold, Heat)  |
| `time_spent` |  Total time (in minutes) the user spent on the landing page  |
| `pages_visited` | Number of pages the user viewed during the session  |
| `conversion_flag` |Binary flag (0/1) indicating whether the user converted (signed up or made a purchase)   |
| `conversion_type` |  Type of conversion achieved (Signup or Purchase)  |
| `traffic_source` | Source of traffic (Organic, Paid, Social, Referral)|
| `product_purchased` | List of products purchased (if applicable)|
| `revenue` | Total revenue generated from the transaction (if purchase was made)|
| `payment_type` |  Payment method used (Card or COD)|
| `card_type` |  Card type if payment was made by card (Amex, Visa, Master) |
| `coupon_applied` |  Whether a coupon was applied (Yes/No) |
| `bounce_flag` | Indicates if the session was a bounce (only one page visited)|

## 🧮 Statistical Approach
| Method | Purpose |
|------|------|
| Proportion Z-test | compare the effects of landing page designs on conversion rates, number of pages visited, and duration; compare the effects of age group and gender on conversion rates; compare the effects of marketing channel on conversion rate and bounce rate|
| Kruskal-Wallis Test | compare the effects of age group and gender on average sales   |

## 📈 Results
### The Effects of Landing Page Designs on Conversion Rates
<img width="424" height="236" alt="image" src="https://github.com/user-attachments/assets/ca1f630e-a286-488f-9647-baa34aa12315" />

### The Effects of Landing Page Designs on Number of Pages Visited and Duration
<img width="521" height="154" alt="image" src="https://github.com/user-attachments/assets/2da61293-7d06-4356-aa36-75aa5fb80c48" />

### The Effects of Age Group on Conversion Rates and Average Sales
<img width="296" height="190" alt="image" src="https://github.com/user-attachments/assets/0400b0d3-c57b-42c2-8272-60594ad63017" />

### The Effects of Gender on Conversion Rates and Average Sales
<img width="287" height="168" alt="image" src="https://github.com/user-attachments/assets/738bb9ad-60b2-42f5-b965-6f5ba08a67f2" />

### The Effects of Marketing Channel on Conversion Rates
<img width="553" height="209" alt="image" src="https://github.com/user-attachments/assets/0bf46ed9-5906-4a42-96fe-a768e0f8646d" />

## ✍ Recommendations
### Landing Page Colors
1. Implement cold color theme on the landing page
2. Investigate other factors (button, layout, font color) that can significantly impact customer engagement (page views and session duration) and do another A/B testing

### Marketing Channel
1. Focused on using organic, paid, and referral channels instead of social media
2. Scale up successful campaign on paid channel
3. Optimize SEO on organic channel
4. Analyze customer behavior on social media and improve ads on social media

### Customer Demographic 
1. Prioritize adult customers
2. Boost Average Order Value (AOV) among adult customers by offering product bundling or giving recommendations based on purchase history
Encourage purchase frequency by giving purchase points which can be redeemed for discounts
3. Recommending high-margin products to male customers


