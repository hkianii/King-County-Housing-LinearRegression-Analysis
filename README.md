# Multiple Linear Regression with Interaction: King County House Prices

## Project Overview
This project was developed as part of a class assignment focusing on practical applications of Multiple Linear Regression with interactions. Utilizing the King County House Data, our analysis aims to understand the factors influencing the rising house prices in the local area. This project is intended to provide real-world insights by applying theoretical knowledge from our coursework.

## Dataset
The dataset used in this analysis, `kc_house_data.csv`, represents housing sales in King County. It includes features such as the number of bedrooms, square footage, and sale price. This dataset was chosen for its relevance to our local community and the current concerns regarding housing affordability.

## Analysis
The core of our analysis lies in constructing a Multiple Linear Regression model, incorporating interaction terms to explore the combined effects of different housing features on sale prices. The R programming language, along with various packages like `corrplot`, `gridExtra`, and `Metrics`, was used to perform this analysis.

## How to Run
1. Ensure R and the necessary packages (`corrplot`, `gridExtra`, `Metrics`) are installed on your machine.
2. Download the `Group7_Hung_Huang_Ijaz_Kiani_DA310_FinalProject.R` and `kc_house_data.csv` files from this repository.
3. Place both files in the same directory.
4. Open the R script in your R environment and run it to replicate our analysis and view the results.


## Results and Discussion
Our regression analysis revealed significant variables impacting house prices in King County, including the grade of the house, square footage of living areas, and views. Transformation of the price variable to its logarithmic form helped in stabilizing variance, enhancing the model's performance.

Key findings include:
- Higher-grade houses tend to have higher prices.
- Larger living areas (both interior and neighboring properties) are associated with higher house prices.
- Houses with better views are valued higher in the market.

Our model's accuracy was assessed using the Root Mean Square Error (RMSE), which provided an estimate of the deviation of predicted prices from actual sale prices.

The normality and homoscedasticity assumptions were verified, indicating a good fit for the model. Visual analyses through scatterplots and box plots provided additional insights into the relationship between house features and pricing.

These findings can assist in understanding market dynamics and inform potential buyers or sellers in the King County area.


## Contributions
This project was a collaborative effort by Kevin Huang, Joyce Hung, Afshan Ijaz, and Hamza Kiani for the DA310 course under the guidance of Professor Charlene Cheng. We welcome feedback and contributions to our analysis.
