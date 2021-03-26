# Apartment-Price-Prediction

This project was completed by the following team:
* Paula Demacker
* Peter Mankiewich
* Chenzhi Pan
* Jiajian Guo

### Project Summary
As a team, we set out to develop a model to predict apartments prices in South Korea based on various features about the location and attributes of the particular apartment. We used a dataset from Kaggle for our analysis. Housing prices is an area of big concern all over the world given our ever growing population. South Korea, a country in which about 59.9% of all homes are apartments, is no exception. We will specifically be examining apartments in order to understand which factors contribute most to apartments prices, and to predict prices for apartments that we have not yet seen. For a family searching for a home in South Korea, this model can help them to understand if they are overpaying. For example, if they know the location of the apartment and some basic information, such as the number of rooms, they can determine if they are being offered a fair price. In addition, the landlord or seller of the property can use this model to calculate a fair price for the apartment.


Our Dataset contains the following features:

* transaction_real_price: the price that the apartment was sold at (target variable)
* key: increments by one based on the row number
* apartment_id: a unique identifier for the building in which the apartment is found
* transaction_year_month: the year and month the transaction took place
* transaction_date: the date on which the transaction took place
* year_of_completion: the year the apartment was built
* exclusive_use_area: the total floor area of the building
* floor: the floor number that the apartment building is located
* latitude: latitude of the apartment
* longitude: longitude of the apartment
* address_by_law: address represented numerically
* total_parking_capacity_in_site: the number of parking spots for the entire building complex in which the apartment is located (potentially there could be multiple separate buildings in the site)
* total_household_count_in_site: The number of separate households located in the apartment complex
* apartment_building_count_in_sites: the number of separate apartments building in the apartment complex
* tallest_building_in_sites: the number of floors of the tallest building in the apartment complex
* lowest_building_in_sites: the number of floors of the shortest building in the apartment complex
* heat_type: the type of heat available tot he apartment (individual, central, district)
* heat_fuel: the type of heating fuel used by the apartment (gas, cogeneration)
* room_id: unique identifier for the apartment
* supply_area: Total site area (area of the entire apartment complex)
* total_household_count_of_area_type: Count of households in the immediate area
* room_count: the number of rooms in the apartment
* bathroom_count: the number of bathrooms in the apartment
* front_door_structure: the structure of the entrance to the apartment (corridor, stairway, mixed)