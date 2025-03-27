# Car-Dataset-EDA
**Dataset Description**
You are given a car dataset with the following columns:

Make: The manufacturer of the car (e.g., Toyota, Ford, BMW).

Model: The specific model name of the car.

Year: The production year of the car.

Engine Fuel Type: Type of fuel the car uses (e.g., gas, diesel, electric, hybrid).

Engine HP: The horsepower of the car's engine.

Engine Cylinders: The number of cylinders in the car's engine.

Transmission Type: The type of transmission in the car (e.g., automatic, manual).

Driven_Wheels: The type of drivetrain (e.g., front-wheel drive, rear-wheel drive, all-wheel drive).

Number of Doors: Number of doors the car has (e.g., 2, 4).

Market Category: The market segment the car belongs to (e.g., SUV, sedan, luxury).

Vehicle Size: The size category of the car (e.g., compact, mid-size, large).

Vehicle Style: The style of the vehicle (e.g., coupe, convertible, hatchback).

highway MPG: The estimated miles per gallon on the highway.

city mpg: The estimated miles per gallon in the city.

Popularity: A numerical value indicating how popular the car is in the market.

MSRP: The Manufacturer's Suggested Retail Price of the car.

**Deliverables**
A cleaned dataset with all missing data addressed, data types fixed, and filters applied.

All new features (columns) created as described in the feature engineering section.

Visualizations that answer the following questions:

What trends exist in pricing (MSRP) and market size (Vehicle Size)?

How does horsepower (Engine HP) relate to price (MSRP)?

Is there a significant difference in price (MSRP) for different drivetrains (Driven_Wheels)?

How do MPG (city mpg and highway MPG) trends change with transmission type (Transmission Type)?

**Insights**

**Pricing vs. Vehicle Size:** Compact and mid-size vehicles have similar pricing differences, while larger vehicles tend to be priced higher, indicating a possible premium for size.

**Horsepower and Price:** Horsepower is concentrated at lower price points, with some notable outliers, suggesting that more powerful vehicles might be priced unpredictably.

**Drivetrain and Price:** Drivetrain type doesn’t show a significant price difference, but there are outliers, particularly with all-wheel-drive vehicles.

**MPG and Transmission Type:** Direct-drive transmissions have the highest average MPG, with a sharp bell-shaped distribution, showing a clear efficiency trend.
