# Car Price Analysis Using R

## Tiny Project

This project performs exploratory **Car Price Analysis Using R and R Markdown** and follows the techniques demonstrated in Practical 8, 9 and 10.

### Objectives

- Import and inspect car-price data
- Check and clean the data
- Calculate descriptive statistics
- Analyze categorical variables
- Create charts and plots
- Study relationships between selling price and numerical variables
- Interpret findings and provide a conclusion

### Files

- `Tiny_Project.Rmd` - complete R Markdown source
- `car_data.csv` - sample car-price dataset
- `data_dictionary.csv` - description of dataset variables
- `Tiny_Project.html` - rendered report
- `README.md` - project documentation
- `requirements.txt` - requirements
- `screenshots/` - supporting graphs

### Requirements

- R
- RStudio
- R Markdown
- knitr
- rmarkdown

The analysis itself uses base R functions.

### How to Run

1. Open `Tiny_Project.Rmd` in RStudio.
2. Keep `car_data.csv` in the same folder.
3. Make sure R Markdown is installed.
4. Click **Knit**.
5. Select HTML output if prompted.

### Dataset

The dataset contains 40 car records and 10 variables:

`Car_ID`, `Car_Name`, `Year`, `Present_Price_Lakh`, `Kms_Driven`, `Fuel_Type`, `Seller_Type`, `Transmission`, `Owner`, and `Selling_Price_Lakh`.

The dataset is a structured sample prepared for this academic Tiny Project. Prices are for demonstrating data-analysis techniques and are not live market quotations.

### Analysis Covered

1. Data importing
2. Dataset structure and summary
3. Missing-value checking
4. Duplicate checking
5. Data-type checking
6. Mean, median, variance and standard deviation
7. Fuel-type and transmission analysis
8. Selling-price bar plot
9. Kilometres-driven histogram
10. Present-price vs selling-price scatter plot
11. Kilometres-driven vs selling-price scatter plot
12. Correlation analysis
13. Findings and conclusion

### Academic Note

This project combines R code, outputs, graphs and written interpretation in one R Markdown report suitable for the Tiny Project requirements.


## Important
Extract the ZIP completely before opening `Tiny_Project.Rmd`. Keep `car_data.csv` in the same folder as the Rmd. The import code also searches nearby parent folders if RStudio uses a different working directory.
