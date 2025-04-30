Subject: Insights from Data Analysis and Recommendations

Hi Team,

Good morning!

I conducted an analysis of our user, transaction, and product data and would like to share key insights and action items with you.

One important trend is related to user growth as a metric for Fetch's performance. We’ve experienced significant growth in our user base, particularly in earlier periods, with annual increases reaching as high as 819%. However, we've noticed a decline of approximately 42% in the most recent year, suggesting potential challenges in user engagement or market saturation. This growth pattern indicates a strong initial product-market fit, but we may need to reevaluate our strategies to sustain this momentum. Currently, our user demographic largely consists of females aged 25 to 55, which could serve as a foundation for our next marketing campaign.

While this insight are valuable, I want to highlight some data quality issues:

1.Missing Values: We are seeing significant null values in critical metrics such as user birth date, state, gender, receipt barcode, final sale, and brand. These omissions may arise from optional fields during user registration. Collecting accurate birthday and gender information is essential for understanding our customer demographics. Implementing a more user-friendly process for gathering this information could improve our data quality.

2.Duplicate Records: We have identified duplicates in the receipt ID and Barcode fields within the transaction data, indicating that customers may scan the same receipt multiple times. This necessitates the removal of invalid records to ensure accuracy in our analysis. We might consider solutions within the app to prevent duplicate scans.

3.Incorrect Mapping Between Transactions and Users: A significant number of user IDs in the transaction data do not match those in the user table. This prevents us from accurately linking scanned receipts back to customer profiles, limiting our ability to analyze user behavior effectively.


To enhance our data environment and support ongoing business growth, I would appreciate your guidance on the following:

1.Do we have documentation or insights regarding how user IDs are generated and logged, particularly in the transactions table.

2.Collaboration with the Product Team: Can we arrange a meeting with the product team to discuss how they gather customer information? This would help us identify recommendations for improving data collection practices to reduce missing values and ensure consistency.

3.Enhancements to Data Collection Practices: I’d like to hear your suggestions for improving how we capture repeat engagements from users.


Thank you for your time, and I look forward to your insights. And I am also happy to pull up with you in a call to discuss more.

Best regards,

Wanruo Li
Senior Data Analyst
