# Freshco-Hypermarket-into-MSExcel
Freshco Hypermarket, situated in HSR, Bangalore, has established itself as a prominent supermarket in the region, catering to a wide range of customers. In response to evolving customer needs and to enhance convenience, Freshco introduced a home delivery service in the year 2021.Business Metrics: Completion rate : This refers to the rate at which orders are completed (Order successfully delivered / Total order placed).

Customer Lifetime value : It refers to the total revenue generated per customer. Usually this number is defined across various time period such as 3 month LTV, 6 month LTV or 12 months LTV. However, you don’t need to consider specific time period for this business case. For example, if a person placed 15 orders and paid cumulative 4500 rupees to Freshco, the LTV for the customer is 4500 (excluding discount).

Acquisition month : First month of transaction by the customer. For example, if you have purchased your first order at Amazon on 15th Jan , 2017, then you as a customer, got acquired by Amazon in Jan 2017. For a user, the acquisition month is always going to be same, it doesn’t change with subsequent transactions. It’s like your birth date, which is always going to be same.

Delivery Area : It refers to the designated drop-off location where a product or package is intended to be delivered. Refer order geo drop column for this.

Slot definition : A time slot is a specific interval when a customer chooses to place an order from a specific store or location. Example of time slots: morning, afternoon, evening, night, and late-night.

Morning: Orders placed between 5am to 12pm Afternoon: Orders placed between 12pm to 5 pm Evening: Orders placed between 5pm to 8pm Night: Orders placed between 8pm to 11pm Late Night: Orders placed between 11pm to 5am Customer acquisition source : It is the source from which a customer got acquired to the platform.

For example, Let’s say you are not aware about Freshco Hypermarket or never purchase anything from it. Now suddenly, you see a biscuit ad by Freshco on a facebook page. You like the ad and place your first order on the Freshco website, then you are acquired by Freshco through the “facebook” source. The details for source wise acquisition is mentioned in the SourceData csv. Now imagine if there are 2 customers, got acquired through facebook channel. One has LTV of 500 and another one has 200. Then the “Aggregated LTV” for facebook channel is going to be (500+200)/2 = 350. Same kind of analysis can be extended to any level.

Overall delivery time :It refer as the time difference between the order placed time and the completion time of the delivery process. It measures the total elapsed time required for the entire delivery process (Order time – completed delivery time).

The overall delivery time can be broken down into following-

Order to Arrival : Order time to Partner Store reach.

Arrival to pickup : Partner Store Reach Time to Partner Start for Delivery Time.

Pickup to Delivery : Partner Start for Delivery Time to Completed/Cancelled Timestamp.

Use both the datasets to solve all of the following questions. You need to create data view for every question and write your brief summary inference on every analysis (Order Level Analysis, Completion Rate Analysis, Customer Level Analysis, Delivery Analysis, Product Level Analysis). Make sure that you submit/upload both (excel working file and Doc report) files using zip.

Task to do - Order level Analysis :

Identify order distribution at slot and delivery area level.
Identify the areas having highest increase in monthly orders (from Jan to Sep) in absolute orders.
Calculate delivery charges as a percentage of product amount at slot and month level.
Calculate discount as a percentage of product amount at slot and month level.
Calculate discount as a percentage of product amount at drop area and slot level.
Completion Rate Analysis :

Identify Completion rate at slot vs day of the week (Sunday to Saturday) level. Can you spot some pattern in the data?
Calculate completion rate at drop area level.
Completion rate at number of products ordered level. For this first you need to create a column having number of product against every order.
Give you analysis on the any pattern you observe in the completion rate.
Customer Level Analysis ;

Identify Completion rate at source level.
Calculate LTV for every customer.
Calculate aggregated LTV at customer acquisition source level. Refer to aggregated LTV example.
Calculate aggregated LTV at acquisition month level. Refer to aggregated LTV example.
What is the average Revenue(Product amount after discount) per order at different customer acquisition source level?
What is the average Revenue(Product amount after discount) per order at acquisition month level?
Is there any pattern in order rating across slots, number of items placed, delivery charges, discount. For example, there might be an insight from the data that orders placed during late night are generally rated high. While orders placed in early morning are not rated high. OR orders having more than 5 items are generally rated high.
Delivery Analysis :

Calculate average overall delivery time at month and delivery area level.
Calculate average overall delivery time at month and weekday/weekend level. You might need to create a column which will tag every date to either weekday or weekend.
Calculate average overall delivery time at slot level. Refer to the definition of slot.
Do you see any pattern in delivery charges with slot or delivery area.
Do you see any pattern in delivery time and delivery area. If yes then find out logical reason.
