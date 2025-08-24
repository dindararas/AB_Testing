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
