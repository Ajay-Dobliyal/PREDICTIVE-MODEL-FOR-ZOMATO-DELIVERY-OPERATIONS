# PREDICTIVE-MODEL-FOR-ZOMATO-DELIVERY-OPERATIONS
Supervised ML project aimed at forecasting the 'Time-taken' by delivery personnel, leveraging diverse factors
Key methodologies included utilizing the **Haversine formula** for precise distance calculations based on latitude and longitude coordinates. 
Utilized Lazypredict to systematically evaluate and compare various predictive models, ensuring the selection of the most accurate and efficient model for deployment.

**Features:**
ID: Unique identifier for each delivery.
Delivery_person_ID: Unique identifier for each delivery person.
Delivery_person_Age: Age of the delivery person.
Delivery_person_Ratings: Ratings assigned to the delivery person.
Restaurant_latitude: Latitude of the restaurant.
Restaurant_longitude: Longitude of the restaurant.
Delivery_location_latitude: Latitude of the delivery location.
Delivery_location_longitude: Longitude of the delivery location.
Order_Date: Date of the order.
Time_Ordered: Time the order was placed.
Time_Order_picked: Time the order was picked up for delivery.
Weather_conditions: Weather conditions at the time of delivery.
Road_traffic_density: Density of road traffic during delivery.
Vehicle_condition: Condition of the delivery vehicle.
Type_of_order: Type of order (e.g., dine-in, takeaway, delivery).
Type_of_vehicle: Type of vehicle used for delivery.
Multiple_deliveries: Indicator of whether multiple deliveries were made in the same trip.
Festival: Indicator of whether the delivery coincided with a festival.
City: City where the delivery took place.
Time_taken (min): Time taken for delivery in minutes.
