## Latar Belakang
Portugal merupakan salah satu negara yang terletak di ujung barat daya Eropa. Banyak wisatwan yang berkunjung ke portugal untuk berlibur,  
tapi ada juga yang berkunjung untuk urusan bisnis atau yang lain nya. Selama berkunjung pelanggan akan menginap di hotel.  
Karena banyak nya pengunjung yang memesan hotel, maka banyak pengunjung yang memesan hotel dari jauh hari. 
Namun setelah pemesanan banyak pelanggan yang tiba-tiba mengcancel pesanannya.  

Maka dalam kesempatan ini saya akan mencoba membuat sistem yang dapat memprediksi pelanggan mana yang akan cancel menggunakan machine learning

## Kolom yang digunakan sebagai Feature
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

Dengan Target kolom adalah **is_canceled** sebagai y

## Preprocess
1. One Hot Encoding ,Kolom = Hotel
2. Binary Encoding, Kolom = country,market_segment,customer_type
3. Robust Scaler, Kolom = lead_time,days_in_waiting_list,booking_changes,previous_cancellations,previous_bookings_not_canceled
4. Oversampling, Menggunakan SMOTE

## Algoritma Machine Learning
1. logistic regressi
2. KNN
3. Decision Tree
4. Random Forest
5. XGBoost
6. Voting Classifier
7. Stacking Classifier
