# Predicting House Prices and Identifying Key Value Drivers in King County

![home](https://github.com/foaxy/Phase2_Project/blob/main/Images/home.jpg)

## Business Understanding

The BlueWave real estate agency aims to leverage the King County House Sales dataset to gain valuable insights into the factors that influence house prices and provide informed recommendations to homeowners, buyers, and sellers. By analyzing the dataset's various attributes, such as the number of bedrooms, bathrooms, square footage of living space, condition, and grade of the house, the agency intends to address key challenges in the real estate market and enhance its services.

This project will empower the real estate agency to provide more accurate and comprehensive services to its stakeholders. By leveraging the insights gained from the dataset, the agency can better guide homeowners in understanding their property's value, assist buyers and sellers in making informed decisions, and offer tailored recommendations for home renovations that can significantly impact property values.

## Problem Statement

#### Business Problem 1: Predicting House Prices

The real estate agency wants to provide accurate price predictions for houses in order to assist homeowners, buyers, and sellers in making informed decisions. By analyzing historical sales data and relevant features such as the number of bedrooms, bathrooms, square footage of living space, and overall condition of the house, the agency aims to develop a predictive model that can estimate the sale price of a house accurately. This will help homeowners understand the potential value of their property and enable buyers and sellers to negotiate fair prices.

#### Business Problem 2: Identifying Key Factors for Home Value

The real estate agency wants to identify the key factors that significantly influence the value of residential properties. By analyzing the provided dataset, including features such as the number of bedrooms, bathrooms, square footage, condition, and grade of the house, the agency aims to uncover which attributes have the most substantial impact on the sale price. This analysis will provide valuable insights for homeowners looking to increase the value of their homes through renovations or improvements and guide the agency in advising clients on potential value-boosting strategies.

#### Business Problem 3: Recommending Home Renovations for Value Enhancement

The real estate agency wants to offer recommendations to homeowners on specific home renovations that can potentially increase the estimated value of their properties. By examining the dataset and considering relevant features such as the number of bedrooms, bathrooms, square footage, condition, and grade of the house, the agency aims to identify the renovation areas that have a significant positive impact on the sale price. The agency can then provide personalized advice to homeowners, suggesting improvements or modifications that can maximize the value of their homes in the real estate market.

## Main Objective

The primary objectives of this project are as follows:

- **Accurate Price Prediction:** The real estate agency seeks to develop a robust predictive model that accurately estimates the sale price of residential properties.

- **Identifying Key Value Drivers:** The agency aims to identify the primary factors that significantly influence the value of houses in the King County area. By analyzing the dataset, including attributes such as the number of bedrooms, bathrooms, square footage, condition, and grade of the house, the agency aims to gain insights into the aspects that have the most substantial impact on sale prices. This knowledge will enable the agency to provide valuable guidance to homeowners on potential value-boosting strategies.

- **Endorsing Value-Enhancing Renovations:** The real estate agency intends to offer personalized recommendations to homeowners on home renovations that have the potential to increase the estimated value of their properties. By leveraging the dataset and analyzing the relationships between renovation projects and sale prices, the agency aims to identify specific areas of improvement that have a significant positive impact on property values. This information will enable the agency to advise homeowners on renovation strategies that maximize their return on investment and enhance the marketability of their homes.

## Data Understanding

The dataset provided for this project is the King County House Sales dataset, which contains information on residential property sales in the King County area. The dataset includes various attributes that describe the properties and their associated sale prices. The dataset has the following columns:

* `id` - Unique identifier for a house
* `date` - Date house was sold
* `price` - Sale price (prediction target)
* `bedrooms` - Number of bedrooms
* `bathrooms` - Number of bathrooms
* `sqft_living` - Square footage of living space in the home
* `sqft_lot` - Square footage of the lot
* `floors` - Number of floors (levels) in house
* `waterfront` - Whether the house is on a waterfront
* `view` - Quality of view from house
* `condition` - How good the overall condition of the house is. Related to maintenance of house.
* `grade` - Overall grade of the house. Related to the construction and design of the house.
* `sqft_above` - Square footage of house apart from basement
* `sqft_basement` - Square footage of the basement
* `yr_built` - Year when house was built
* `yr_renovated` - Year when house was renovated
* `zipcode` - ZIP Code used by the United States Postal Service
* `lat` - Latitude coordinate
* `long` - Longitude coordinate
* `sqft_living15` - The square footage of interior housing living space for the nearest 15 neighbors
* `sqft_lot15` - The square footage of the land lots of the nearest 15 neighbors

## Conclusion

Based on the regression model results, we can conclude that certain factors have a significant impact on house prices:

- *Waterfront Location:* Houses situated on waterfronts have a substantial positive effect on the house price. The coefficient of the "waterfront_YES" variable suggests that having a waterfront location significantly increases the price. Buyers often perceive waterfront properties as desirable and are willing to pay a premium for the scenic views and access to water-related activities.

- *Luxurious Features:* The presence of luxurious features, as indicated by variables such as "grade_Better," "grade_Excellent," "grade_Luxury," and "grade_Mansion," has a significant positive influence on house prices. These features can include high-quality construction, upscale finishes, and premium amenities. Properties with superior grades tend to command higher prices due to their perceived value and exclusivity.

- *House Condition:* Maintaining a house in good condition is crucial to avoid a decrease in its value. The coefficient of the "condition_Good" variable suggests that houses in good condition tend to have higher prices. Buyers are generally attracted to properties that are well-maintained, free from significant flaws or deficiencies, and ready for immediate occupancy.

## Recommendations

Based on these findings, the real estate agency should consider the following recommendations:

- **Emphasize Waterfront Properties:** Highlight the waterfront locations of properties in marketing materials and listing descriptions. Showcase the unique features and benefits associated with waterfront living to attract potential buyers and justify higher price expectations.

- **Enhance Luxurious Features:** Encourage homeowners to invest in upgrades and renovations that add luxurious elements to their properties. This could include improving the quality of materials, incorporating upscale amenities, and enhancing the overall aesthetic appeal. These improvements can increase the perceived value of the property and justify higher listing prices.

- **Promote Proper Maintenance:** Educate homeowners on the importance of regular maintenance and timely repairs. Encourage them to address any issues promptly to preserve the condition of their properties. This will help maintain the market value and prevent potential price depreciation due to neglect or deterioration.

By focusing on these recommendations, the real estate agency can help homeowners maximize their property values and assist buyers in finding houses with desirable features.

## Non-Technical Presentation

Click here [Link](https://docs.google.com/presentation/d/1Sgbs_X1BPQPpGx0ROMIyjm3qvhVgisnv88GU7RviOTM/edit?usp=sharing) to view the non-technical presentation.
