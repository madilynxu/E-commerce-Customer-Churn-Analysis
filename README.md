# E-commerce Customer Churn Analysis & Prediction
<img src="Churn.png" width="500">

## Project Overview
The goal of this project is to predict customer churn and perform customer segmentation for an e-commerce platform. By identifying at-risk customers, it provides insights to reduce churn and improve customer retention. Additionally, customer segmentation is performed to tailor strategies for different customer groups, enhancing the platform's retention efforts.

## Key Insights

- Churn Prediction:

The churn rate across the 5,630 customers is 16.84%, with a key predictor being the customer’s tenure.

The most important predictors of churn include tenure, cash back amount, complaints, and order categories.

- Model Performance:

The XGBoost model performed best with a recall score of 98%, successfully identifying the majority of at-risk customers.

Compared models: Logistic Regression (79% recall), SVM (94% recall), Random Forest (93% recall), and Stacking (92% recall).

A final XGBoost model was selected for its strong performance and low computational complexity.

- Customer Segmentation:

Using K-Means clustering and RFM analysis, customers were segmented into four groups: Occasional Shoppers, Premium Enthusiasts, Price-conscious Bargain Hunters, and Loyal Regulars.

Tailored strategies were proposed for each segment, such as "Perfect for You" campaigns for occasional shoppers and VIP experiences for premium enthusiasts.

- Customer Lifetime Value (CLV):

High-value customers (with CLV > $373.33) have lower churn rates (5.44%).

A significant portion of the potential churn is from high-value customers, with a revenue loss potential of $20,776.83.

## Recommendations
- Focus on high-value customers: Implement personalized programs for customers with a CLV above $373.33, as they have lower churn rates and higher revenue potential.

- Segment-specific retention strategies: Develop tailored campaigns for each customer segment based on their unique behaviors and preferences.

- Improve feature tracking: Include additional metrics like product return history and customer referral activity for better churn prediction.
