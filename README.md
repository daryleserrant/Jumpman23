# Jumpman23 -- New Market Analysis
 
## Background 
 
Jumpman23 is an on-demand delivery platform connecting “Jumpmen” and customers purchasing a variety of goods. Jumpman23 will send Jumpmen to merchants to purchase and pickup any items requested by the customer. Whenever possible, Jumpman23 will order the requested items ahead to save the Jumpmen time. Each time a Jumpman23 delivery is completed, a record is saved to the Jumpman23 database that contains information about that delivery. Jumpman23 is growing fast and has just launched in its newest market -- New York City. 
 
## Challenge 
 
The CEO of Jumpman23 has just asked you “how are things going in New York”. He has mentioned to you that he’s heard reports of data integrity issues. Please think through the CEO’s ask and present to both the CEO and the CTO, in any format you choose, an analysis of the market. In addition, dive into the reports on data integrity issues and if they indeed exist, outline where they may be and how they may impact the analysis. The CEO is a visual learner, the CTO loves to see code and technical work,  and both are obsessed with maps.  
 
## Available Data 
 
You have been provided one small csv file with a sample of data. This file includes:

* job_ID  - a unique identifier of a delivery 
* customer_id - a unique identifier for the Jumpman23 customer 
* jumpman_id - a unique identifier for the Jumpman who completed the delivery 
* vehicle_type - The method of transport the Jumpman used to complete the delivery 
* pickup_place - The name of the Pickup location 
* place_category - A categorization of the Pickup location 
* item_name - the name of the item requested 
* item_quantity - how many of that item was requested 
* item_category_name - categorization provided by merchant, think “appetizers”, “soups” etc 
* how_long_it_took_to_order - how long it took to place the order
* pickup_lat - the coordinates of the pickup location 
* pickup_lon - the coordinates of the pickup location 
* dropoff_lat - the coordinations of the dropoff location  
* dropoff_lon - the coordinations of the dropoff location  
* when_the_delivery_started - localized timestamp representing when the delivery began 
* when_the_Jumpman_arrived_at_pickup - localized timestamp representing when the Jumpman arrived at the pickup location 
* when_the_Jumpman_left_pickup - localized timestamp representing when the Jumpman left the pickup location 
* when_the_Jumpman_arrived_at_dropoff - localized timestamp representing when the Jumpman reached the customer
