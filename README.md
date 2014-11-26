# Order Fulfillment Service
 Our service is made for receive orders which comes from customers and check the products in stock whether it is available or not and let user goes through payment and shipping and also the service will track the order until they are fulfilled or approved and the customer can check their order status. 
 This service requires other services to succeed its goal such as Product Service, Payment Service and Shipment Tracking Service.

## What is Order Fulfillment ?
* Order fulfillment is the complete process from point of sales inquiry to delivery of a product to the customer. Sometimes Order Fulfillment is used to simply describe the act of distribution (logistics) or the shipping function, but in the broader sense it refers to the way firms respond to customer orders, and the process they take to move products from those orders, to the customer.
* In simpler terms, Order Fulfillment is everything that a seller does from the moment an order for a product is received, to the customer having their purchase in their hands. Order Fulfillment also includes the processes involved in receiving products to sell, storing those products, and providing inventory control of those products.
* From http://www.fulfillmentwarehouse.biz/what-is-fulfillment.asp

## Stakeholder
* Order Fulfiller

## Use Stories/Visions

* Order Fulfiller
```
 As an order fulfiller, I would like to see all the orders.
 As an order fulfiller, I would like to see the order by order id.
 As an order fulfiller, I would like to fulfill customers’ order(s).
 As an order fulfiller, I would like to delete an order.
```

## Use Cases
* UC1: Order Item
```
Stakeholder : Customer
Success scenario : The order is created successfully.
Description : Customer makes an order which contains product(s) and order it.
```
* UC2: See all orders
```
Stakeholder : Order fulfiller
Success scenario : The  fulfiller can view all incoming orders.
Description : Show all incoming orders from all customers and the status of each order to the order fulfiller.
```
* UC3: See specific order (by id)
```
Stakeholder : Order Fulfiller
Success scenario : The fulfiller can view details of each specific order by order id.
Description : Show the specific order and the status of that order.
```
* UC4: Edit order (during order)
```
Stakeholder : Customer
Success scenario : Customer can edit their order.
Description : Customer can edit their order before submit the order. After the fulfillment, 
customer will not be able to change their order.
```
* UC5: Cancel order (during order)
```
Stakeholder : Customer
Success scenario : Customer can cancel their current order.
Description : Customer can cancel their current order during their order before submitting the order.
```
* UC6: Fulfill order
```
Stakeholder : Order Fulfiller 
Success scenario : The order was fulfilled(approved) and the products are ready to ship.
Description : The order fulfiller can fulfill or approve the order after the payment is done.
```
* UC7: Check order’s status 
```
Stakeholder : Customer
Success scenario : The order status displayed.
Description : Customer can view the order’s status that it is fulfilled, paid or waiting.
```
* UC8: Order fulfillment status (for the race conditions) 
```
Stakeholder : Order Fulfiller 
Success scenario : The order fulfillment status displayed.
Description : Order fulfiller can view order fulfillment status that it is fulfilled or not.
```
* UC9: Delete Order
```
Stakeholder : Order Fulfiller 
Success scenario : The order is deleted
Description : Order fulfiller can delete the specific order from the order list. 
```
## API Document
* [Online API Document](https://docs.google.com/document/d/1L6OOY9A68hwQ-QJjaWAAZAKGnS31ZiXh1P3-_lgny4s/edit?usp=sharing)

## Design
* [Domain Design of Order](https://docs.google.com/drawings/d/1lcKgqQiR_A4yD_TW3QE5BHE_GkrkW-KHhvpIsrvY0Dw/edit?usp=sharing)
 
## Mockup
---Coming soon---

## Out of scope
* Customer authentication (It should be like ordering KFC or at least the authentication should be done before.)
* Customer notification

## Group Member
* Eknarin Thirayothin	   5510546239
* Natcha  Chidchob 		    5510546239
* Sarathit  Sangtaweep 	 5510546182
* Natchanon Hongladaromp 5510546034

## Referrences
* https://se.cpe.ku.ac.th/wiki/index.php
* http://www.fulfillmentwarehouse.biz/what-is-fulfillment.asp

