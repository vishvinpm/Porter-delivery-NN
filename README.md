# Porter-delivery-NN

# 📈 Introduction

**Porter**, India's largest marketplace for intra-city logistics, is revolutionizing the delivery sector with technology-driven solutions.
This case focuses on leveraging neural networks to accurately predict delivery
times, a critical aspect of customer satisfaction in logistics.
- With a dataset encompassing various aspects of orders and deliveries, Porter
aims to refine its delivery time estimations.
- Analyzing this dataset can provide significant insights into delivery dynamics, efficiency bottlenecks, and optimization opportunities.
- The insights obtained can enhance Porter's operational efficiency, ensuring
timely deliveries and improving driver-partner allocation


# Problem statement

Porter has a number of delivery partners available for delivering the food, from various restaurants and wants to get an estimated delivery time that it can provide the customers on the basis of what they are ordering, from where and also the delivery partners.

This dataset has the required data to train a regression model that will do the delivery time estimation, based on all those features

As a data scientist at Porter, the task is to analyze the dataset to accurately predict delivery times for different orders. The primary goal is to build a regression model using neural networks, evaluate its performance, and provide insights for optimizing delivery operations.


# **Column Profiling**

---


| Column Name   | Description                                    | Data Type |
| ------------- | ---------------------------------------------- | --------- |
| **market_id** | Identifier for the market where the order was placed. | `float64`  |
| **created_at** | Timestamp of when the order was placed.    | `object` |
| **actual_delivery_time** | Timestamp of when the order was delivered.| `object` |
| **store_id** | Unique identifier for the store fulfilling the order.    | `object` |
| **store_primary_category**  |The category of the store (e.g., American, Mexican). | `object` |
| **order_protocol**|Numeric code representing the mode of order placement            | `float64` |
| **total_items** | Total number of items in the order. | `int64` |
| **subtotal** | The subtotal cost of the order.    | `int64` |
| **num_distinct_items**    | Count of different items in the order   | `int64`   |
| **min_item_price**    | Price of the least expensive item in the order   | `int64`   |
| **max_item_price**    | Price of the most expensive item in the order.  | `int64`   |
| **total_onshift_partners**    | Number of delivery partners available at the time.   | `float64`   |
| **total_busy_partners**    | Number of delivery partners currently busy.   | `float64`   |
| **total_outstanding_orders**    | Number of outstanding orders at that moment. | `float64`   |


---
