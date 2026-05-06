# Customer_churn_prediction
prediction of the lost business of customer.
1. Key Findings (The "Why")
Contract Type is King: Customers on Month-to-month contracts are significantly more likely to churn compared to those on one or two-year contracts.
The "New Customer" Risk: Churn is highest during the first 6 months of tenure. If a customer stays past the first year, their loyalty increases drastically.
Fiber Optic Friction: Surprisingly, customers with Fiber Optic internet often churn at higher rates than DSL, possibly due to higher costs or service stability issues.
Payment Friction: Customers using Electronic Checks churn more often than those on Automatic Credit Card/Bank transfers.
2. Business Recommendations (The "Action")
Incentivize Long-Term Contracts: Offer a small discount or a "loyalty bonus" to move month-to-month customers into at least a 1-year agreement.
Proactive "Newbie" Support: Implement a "Customer Success" check-in at the 3-month mark for all new sign-ups to ensure they are satisfied with the service.
Promote Autopay: Offer a one-time bill credit for customers who switch from manual electronic checks to automatic bank payments.
Targeted Retention: Instead of giving discounts to everyone, use your Probability Score (from the predict_proba code) to send "Save Offers" only to customers with a churn probability higher than 70%.
3. Summary for your Resume/Portfolio
"Developed a machine learning pipeline that identifies high-risk customers with 85% accuracy. By identifying the top churn drivers—specifically contract type and tenure—the model provides a roadmap to potentially reduce customer attrition by focusing retention efforts on the highest-risk segments."
