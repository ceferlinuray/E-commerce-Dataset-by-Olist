# Brazilian E-Commerce Analytics | Power BI

An end-to-end business intelligence project exploring customer purchasing behavior, product and seller performance, order trends, customer reviews, and delivery operations using the Brazilian E-Commerce Public Dataset by Olist.

## 1. Project Overview

This project uses Microsoft Power BI to analyze an e-commerce business operating in Brazil. The objective is to transform raw transactional data into meaningful business insights that help explain purchasing patterns, sales performance, customer behavior, and operational efficiency.

Tools:Power BI, Power Query, DAX  
Dataset: Brazilian E-Commerce Public Dataset by Olist  
Project type: Business Intelligence and Exploratory Business Analysis

## 2. Business Problems

An e-commerce business needs to understand not only how much customers purchase, but also what they buy, how sellers perform, how efficiently orders are delivered, and how customers respond to their shopping experience.

The purpose is to identify patterns, compare performance, and support data-informed business decisions while acknowledging the limitations of the available data.

## 3. Dataset Description

The project uses the Brazilian E-Commerce Public Dataset by Olist, a publicly available dataset containing anonymized e-commerce transactions from Brazil.

The dataset covers orders placed between 2016 and 2018 and contains approximately 100,000 orders. It includes information about customers, sellers, products, payments, reviews, order items, and delivery timestamps.


## 4. Report Pages and Analytical Questions

### Page 1 — Overview

The Overview page provides a high-level view of e-commerce activity.
Key questions answered:

- How does the total product value change over time?
- How many orders and customers are represented in the dataset?
- Which Brazilian states show the highest values for the selected indicators?
- How does order activity vary across the available time period?
- What are the overall patterns in purchasing and business activity?

### Page 2 — Product and Seller Analysis

This page examines product categories, individual products, and seller performance.
Key questions answered:
- Which product categories account for the highest total product value?
- Which products contribute most to the value of items ordered?
- How are product prices distributed?
- Which sellers have the highest total product value and order-item activity?


### Page 3 — Customer Analysis

The Customer Analysis page focuses on purchasing behavior and customer-level patterns.
Key questions answered:
- How many customers place only one order versus multiple orders?
- What proportion of customers make repeat purchases?
- How many orders does the average customer place?
- How is total product value distributed across customers?
- Which customers contribute the highest product value?
- Which payment methods are used most frequently?


### Page 4 — Delivery Analysis

This page investigates delivery speed, delivery outcomes, and their relationship with customer satisfaction.
Key questions answered:
- What is the average delivery time?
- What proportion of orders are delivered on time or late?
- How does delivery performance vary over time?
- Which states or geographic areas show different delivery patterns?
- Is there an observable relationship between delivery delays and review scores?



 Important Data and Measurement Limitations

A key part of responsible analysis is distinguishing what the dataset directly measures from what would require additional information or assumptions.

 Total Product Value Is Not Verified Business Revenue

The main sales-value measure in this project is calculated by summing the `price` column in the `order_items` table.

This represents the recorded value of products in order items. It should not automatically be interpreted as recognized accounting revenue, net revenue, profit, or the complete amount paid by customers.
