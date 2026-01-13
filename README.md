# Real Estate Data Analysis

## Overview
This project analyzes real estate data to explore relationships between property features and house prices. The analysis includes data exploration, visualization, and regression modeling to understand how factors like distance to public transportation impact housing prices.

## Dataset
The dataset used is `Real estate.csv`, which contains 414 entries with the following columns:
- `No`: Transaction ID
- `X1 transaction date`: Date of transaction
- `X2 house age`: Age of the house (years)
- `X3 distance to the nearest MRT station`: Distance to the nearest MRT station (meters)
- `X4 number of convenience stores`: Number of convenience stores nearby
- `X5 latitude`: Latitude coordinate
- `X6 longitude`: Longitude coordinate
- `Y house price of unit area`: House price per unit area

## Analysis Steps
1. **Data Loading and Exploration**:
   - Load the dataset and inspect its structure.
   - Check for missing values (none found in this dataset).

2. **Data Visualization**:
   - Create histograms to visualize distributions of key features:
     - House age
     - Distance to nearest MRT station
     - Number of convenience stores
     - House price per unit area

3. **Regression Analysis**:
   - Perform simple linear regression to model the relationship between distance to the nearest MRT station and house price per unit area.
   - Manually compute the regression slope and intercept.
   - Visualize the regression line overlaid on a scatter plot of the data.

## Results
The regression analysis revealed a negative relationship between distance to the nearest MRT station and house price per unit area:
- **Regression Equation**:  
  \( \text{Price} = -0.0073 \times \text{Distance} + 45.8514 \)
- As distance to the MRT station increases, house price per unit area tends to decrease.

## Visualizations
- Histograms for feature distributions are saved as `histograms.png`.
- Scatter plot with regression line visualizing the relationship between distance to MRT and house price.

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Matplotlib


- SciPy

