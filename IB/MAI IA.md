# Independent Variable
- **GDP per Capita**
- **Urbanization Rate**
- **Internet Penetration Rate**
# Dependent Variable
**Median Fixed Broadband Download Speed**（Mbps）in different contry
___
# RQ
**To what extent can different factors of a country predict the median fixed broadband download speed across countries?**
___
# Procedure
- **Data Collection**
    - Collected 2023 data from reliable sources for each country:
        - Median fixed broadband download speed (Speedtest Global Index)
        - GDP per capita (World Bank)
        - Urbanization rate (World Bank or UN)
        - Internet penetration rate (ITU or World Bank)
- **Data Preparation**
    - Compiled and cleaned the dataset (removed missing or extreme values).
    - Standardized variables where necessary (e.g., scaling).
- **Exploratory Data Analysis**
    - Plotted scatter plots to observe relationships.
    - Checked correlations and variable distributions.
    - Distribution
- **Regression Modeling**
    - Performed single-variable linear regressions for each independent variable.
    - Built a multiple linear regression model using all variables.
- **Model Evaluation**
    - Analyzed R², Adjusted R², and RMSE to assess model performance.
    - Checked residual plots and VIF for multicollinearity and model assumptions.
- **Interpretation & Reflection**
    - Interpreted the coefficients to determine the significance of each factor.
    - Discussed limitations, potential sources of error, and areas for improvement.