Recommendation Systems Project
Overview

ExtraaLearn is a startup offering programs to help students and professionals upskill/reskill. With many leads generated regularly, identifying which leads are likely to convert is key to allocating resources efficiently.

This project uses machine learning to:

Predict lead conversion.

Identify factors driving conversion.

Create profiles of high-potential leads.

Objective

Analyze the leads dataset.

Build an ML model to predict lead conversion.

Determine key factors influencing conversion.

Provide actionable business recommendations.

Approach

EDA & Feature Engineering: Time on website, first interaction channel, profile completion, last activity, referrals, occupation, age.

Modeling: Random Forest Classifier with hyperparameter tuning.

Evaluation: Accuracy, recall, and feature importance.

Key Results

Accuracy: 83% on test data

Recall (Converted Class): 85%

Important factors:

Leads spending more time on the website

Website as first interaction channel

High profile completion

Email & website activity

Referral leads

Occupation & age (professionals and older unemployed individuals more likely to convert)

Business Recommendations

Prioritize leads using model scores.

Enhance website experience to increase engagement.

Optimize mobile app experience to improve conversions.

Encourage profile completion through incentives.

Tailor follow-ups based on last activity.

Leverage referrals for high-quality leads.

Target campaigns by age and occupation.

Monitor and retrain the model regularly.

Tools & Technologies

Python: pandas, numpy, scikit-learn, matplotlib, seaborn

Random Forest Classifier

EDA & Feature Engineering

Conclusion

The Random Forest model provides reliable predictions for lead conversion, identifies key drivers, and offers actionable insights to improve sales and marketing strategies.
