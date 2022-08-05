# California Power Plants Exploration
## by Ahmad Anifowose


## Dataset

The dataset contains information about several power plants in California from 2001 to 2015. It includes data about their nameplate capacity, net generation, summer capacity, capacity utilization, etc
The data was selected from [Kaggle](https://www.kaggle.com/datasets/la-times/california-electricity-capacity).

There are 12631 observations in the dataset with 15 features (year, plant_id, plant_name_gen, operator_name_gen, operator_id_gen, net_generation_mwh,	plant_name_cap,	operator_name_cap, operator_id_cap, state, nameplate_mw, summer_mw, capacity_mwh, capacity_utilization, minimum_year).

The dataset was initially explored to determine what sort of cleaning was required, the data was then cleaned appropriately, and analysed with appropriate visualisations.


## Investigation Overview


> The goal of this presentation is to understand the energy situation in California, determine the capacity of power plants in the state, and how they are being utilized over the years.



## Summary of Findings

The analysis showed the following:

1. The dataset has quite a large number plants in the very_small range. The numbers begin to decline as the capacity rises. 
2. The very small plants consists of about 53%, the small plants are 32%, medium, 11%, large, 3%, and very large, 2%.
3. There is a pretty direct relationship. The summer capacity is almost equal to the nominal nameplate capacity.


## Key Insights for Presentation

1. The power plants with the highest net generation (MWh) have a pretty large capacity of about 2,300 MW compared to the remaining plants.

2. The capacity utilization has pretty low correlation. This could mean that some of the plants were not utilized as much as they should, or they typically consumed more power from the grid than they generated within the period of review.

 