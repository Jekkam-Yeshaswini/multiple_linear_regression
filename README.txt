# Bike Sharing Demand Analysis
> This project analyzes the demand for shared bikes using a multiple linear regression model to identify key factors influencing bike-sharing usage.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The project aims to understand the demand for shared bikes in the American market, particularly after the disruptions caused by the COVID-19 pandemic.
- The business problem being addressed is the declining revenues of bike-sharing companies and the need to develop strategies for recovery and growth.
- The dataset used includes daily bike demand information, along with various meteorological and temporal features affecting usage patterns.

## Conclusions
- The final model equation is: 
  \[
  \text{cnt} = 0.2710 + 0.4461 \cdot \text{atemp} - 0.1379 \cdot \text{windspeed} - 0.1094 \cdot \text{spring} + 0.0340 \cdot \text{winter} + 0.2365 \cdot '2019' - 0.0445 \cdot \text{Jan} - 0.0622 \cdot \text{Jul} + 0.0558 \cdot \text{Sept} + 0.0155 \cdot \text{Mon} - 0.0426 \cdot \text{Tues} - 0.2842 \cdot \text{light rain} - 0.0808 \cdot \text{mist}
  \]
- The model achieved an R-Squared value of 0.833 and an Adjusted R-Squared value of 0.829 on the training dataset, indicating a strong fit.
- On the test dataset, the model maintained an R-Squared value of 0.806 and an Adjusted R-Squared value of 0.778, confirming its predictive capability.
- Residual analysis showed that the error terms were normally distributed, validating the assumptions of the linear regression model.

## Technologies Used
- pandas - version 1.3.3
- numpy - version 1.21.2
- scikit-learn - version 0.24.2
- statsmodels - version 0.12.2
- matplotlib - version 3.4.3
- seaborn - version 0.11.2

## Acknowledgements
- Special thanks to the contributors of the dataset and resources used in this analysis.
- This project was based on the assignment given by IIIT bangalore in association with UpGrad.

## Contact
Created by [@Jekkam-Yeshaswini] - feel free to contact me!
