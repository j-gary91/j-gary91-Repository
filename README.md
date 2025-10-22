FoobHub - a startup online food delivery service aggregator - is an app available to NYC residents that connects independently-operating restaurants outside of Uber Eats/DoorDash/Postmates to customers. It operates the same as other delivery services: the order gets placed, it’s prepared, it’s picked up, and then delivered. However, FoodHub earns its revenue via collecting a fixed margin of the restaurant’s delivery orders; it wants to get a better understanding of all the restaurants in its database to ensure order quality and determine its correlation to the app’s returning customers.

I determined the following through an analysis of a single month’s sales utilizing Python to analyze FoodHub’s orders:
* FoodHub’s restaurants took 20-35 minutes from receiving an order to having it prepared, with the average prep time being 27 minutes.
* On average, customers wait 49.66 minutes for their order from when it’s placed until it arrives.
* Despite this time, and I suspect this is because users live in NYC, FoodHub’s customers who provided feedback on their orders rated them relatively high. In an average month, 1,162 orders are placed through FoodHub - 50.60% of customers rated them 5/5, 33.2% rated them 4/5, and 16.18% rated them 3/5. However, this data only represents a small sample of the customer base because out of the 1,162 orders placed, only 426 customers provided ratings, while 736 did not.
* 64.54% of orders placed cost between $10-$15, indicating that FoodHub’s consumers purchase just single meals.
    * Except for orders costing $25 or $30, which would indicate that these FoodHub orders are for groups or families, order costs negatively correlate with a decrease in overall orders.
* 21.51% of orders placed were for Shake Shack, 12.9% of orders were for sushi, 8.6% were for fried chicken, and the remaining 56.9% were from a variety of Italian restaurants
* The Italian restaurants were also the highest-rated restaurants, except ShakeShack.
* The average delivery time from restaurant to door was 24.16 minutes
* As previously stated, FoodHub earns revenue by collecting a fixed margin on its participating restaurants’ delivery orders, specifically 15% on orders greater than $5 and 25% on orders greater than $20. In the month’s worth of data, I analyzed, FoodHub had a net revenue of $6,166.30.
* While the average meal prep to customer door time is 49.66 minutes, 10.5% of orders exceed this.
* FoodHub has an average weekday delivery time of 28.5 minutes, an average weekend delivery time of 22.5 minutes, and an overall average delivery time of 24.15 minutes.
