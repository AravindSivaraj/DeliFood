# DeliFood
Food delivery app

# DeliFood - Food delivery app

DeliFood is a food delivery and tracking application, which can handles thousands of customers at the same time without blocking or slowing down,
with real time status update of delivery workers and exact status of food preparation.

**Technologies used**
---------------------
Angular(Front end) - For user friendly UI, which provides understandable UX with real time map and status
Springboot (Backend) - Server handles multiple user requests and provide service
Redis (cache) - To increase the response time of the application
Kafka (messaging system) - Handles real time status polling of each delivery worker and return exact current location of them without crashing
