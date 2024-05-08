# Analysis of Crime Against Women in India

## Overview
This analysis focuses on studying crimes against women in India using unsupervised learning techniques. The dataset consists of various crimes against women such as rapes, kidnapping and abduction, dowry death, assault with intent to outrage her modesty, insults to the modesty of women, cruelty by husband or relative, immoral traffic, and indecent representation of women. The data spans from the year 2001 to 2012.

## Methodology
We employ the ARIMA (AutoRegressive Integrated Moving Average) model, which is a time series model, to analyze the trends of crimes against women over time. The ARIMA model is implemented using the `statsmodels` library in Python (`from statsmodels.tsa.arima.model import ARIMA`).

## Analysis
We utilize the ARIMA model to forecast the increase or decrease in each crime for the upcoming 5 years, from 2013 to 2017. By leveraging the time series nature of the data, we aim to understand the trends and patterns in crime rates against women over the specified period.

## Visualization
To visualize the results of our analysis, we plot line graphs depicting the forecasted trends for each crime category. These graphs provide insights into the anticipated changes in crime rates over the forecasted period.

## Conclusion
Through this analysis, we aim to gain a deeper understanding of the dynamics of crimes against women in India and provide valuable insights for policymakers, law enforcement agencies, and advocacy groups to address and combat this pressing issue.
