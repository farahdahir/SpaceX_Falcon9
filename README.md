# **Space X  Falcon 9 First Stage Landing Prediction**
# Overview
The goal of this project was to analyze and predict the successful `landing of the Falcon 9 first stage`. This project utilized data from the `SpaceX API` to provide valuable insights into the factors influencing rocket landing success. Multiple classification models were built, including, Logistic Regression, Support Vector Machine, K-Nearest Neighbors and Decision Trees which emerged as the top-performing algorithm, achieving an accuracy of `94.44%` after hyperparameter tuning. By using the model to accurately determining whether the first stage will land successfully for future launches, the `cost of a launch` can be estimated.

# Business Understanding
The cost of a Falcon 9 launch, at `$62 million`, is notably lower than competitors' offerings, which can exceed `$165 million` per launch. SpaceX's competitive advantage lies in the `reusability of the first stage`, resulting in significant cost savings compared to other providers in the space launch industry. This cost information can be invaluable for potential competitors looking to bid against SpaceX for rocket launch contracts.

# Data Understanding
The dataset for the SpaceX Falcon 9 First Stage Landing Prediction project is sourced from `SpaceX's API`, containing records of Falcon 9 rocket launches. It includes data on launch sites, flight numbers, payload masses, orbit types, and success outcomes. `Exploratory data analysis` revealed insights such as the relationship between launch site and success rates, payload mass, orbit type, and flight number. The line chart below shows the yearly trend indicates that between 2010 and 2013, **all landings were unsuccessful**, success rates increased post-2013 with minor dips in 2018 and 2020, and after 2016, there was consistently over a **50% chance of success**.


![](images/launch_success_yearly_trend.png)

Additionally, launch sites were analyzed to find that all SpaceX sites are located on U.S. coasts, near railways and highways, while maintaining a safe distance from cities. `Feature engineering` was done to obtained important variables that would affect the success rate.

