## Background
Portugal is a country located at the southwest tip of Europe. Many tourists visit Portugal for vacation,
but there are also those who visit for business or other reasons. During the visit, customers will stay at the hotel.
Because many visitors book hotels, many visitors book hotels well in advance.
However, after ordering, many customers suddenly canceled their orders.

So on this occasion I will try to create a system that can predict which customers will cancel using machine learning

## The Feature
1.hotel  
2.lead_time  
3.country  
4.market_segment  
5.customer_type  
6.days_in_waiting_list  
7.booking_changes  
8.previous_cancellations  
9.previous_bookings_not_canceled  
10.is_repeated_guest  

The target column is **is_canceled** 

## Preprocess
1. One Hot Encoding ,Column = Hotel
2. Binary Encoding, Column = country,market_segment,customer_type
3. Robust Scaler, Column = lead_time,days_in_waiting_list,booking_changes,previous_cancellations,previous_bookings_not_canceled
4. Oversampling, Use SMOTE

## Machine Learning Algorithm
1. Logistic Regression
2. KNN
3. Decision Tree
4. Random Forest
5. XGBoost
6. Voting Classifier
7. Stacking Classifier
