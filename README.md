# Global Trade Horizons 2030: Predictive Modelling & Trend Analysis of International Exports
## ABSTRACT
Exports of goods and services is an integral part of the overall GDP of an economy in the age of globalization. Machine learning can be used to predict the growth of exports of goods and services by identifying the pattern followed by an economy’s exports. According to the World Bank, exports of goods and services by an economy represent the value of all goods and other market services sold to non-residents, reflecting the change in ownership. Many machine learning algorithms can be used for export prediction. This project proposes to develop a machine learning model to predict the absolute value of exports in billions (USD). The model is trained on a dataset of historical export volume.

Keywords: Export, Economy, Linear Regression, ARIMA, Data Visualisation, Trend Comparison.

## OVERVIEW
With an ever-increasing rise in trade both domestically and internationally, economies have started taking special interest in its export and import volume. Many economists have argued that more rapid growth of exports can lead to higher economic growth. According to the World Bank, exports of goods and services represent the value of all goods and other market services provided to the rest of the world. They include the value of merchandise, freight, insurance, transport, travel, royalties, license fees, and other services, such as communication, construction, financial, information, business, personal, and government services. They exclude compensation of employees and investment income (formerly called factor services) and transfer payments. The share of exports in Indian GDP has increased from 19.8% in 2015 to 21.2% in 2024, which also indicates the growing relevance of exports in the Indian economy (World Bank). These statistics motivated me to analyse the export volume of various countries using machine learning methods to predict what it’s value might grow to by the year 2030.


## PROJECT GOALS
The aim of the project is to – 
•	perform Exploratory Data analysis (EDA), that is, identify historical growth and outliers.
•	build and validate a Linear Regression model to forecast values for the year 2030.
•	build and validate an ARIMA model to forecast values for the year 2030.
•	compare which algorithm is better suited for this dataset.
•	compare growth trajectories between different economic regions (e.g., Emerging Markets vs. Developed Economies).

## DATA SOURCE
The dataset has been retrieved from the official website of the World Bank. It contains the historical data of exports of goods and services (current US$) from the year 1960 till 2024, for all the countries across the globe. The data consists of 267 rows and 66 columns. The two algorithms used are Linear Regression and ARIMA.

Dataset: https://data.worldbank.org/indicator/NE.EXP.GNFS.CD 
Source: Country official statistics, National Statistical Organizations and/or Central Banks; National Accounts data files, Organisation for Economic Co-operation and Development (OECD); Staff estimates, World Bank (WB)

## FUTURE WORK 
There are many ways to improve the model, such as using it on different datasets with bigger sizes and denser datapoints. An example can be classifying the export data into different industries so that we can find out the exact industry which is making progress and industries which need a bigger push. Future iterations may also include parameters like tariff rates, political stability, presence of natural resources, etc.

## CONCLUSION
This project successfully developed a predictive framework to estimate global export volumes for the year 2030. By applying Linear Regression and ARIMA to over six decades of World Bank data, the model provides a quantitative baseline for understanding trade trajectories. Ultimately, this model serves as a foundational tool for economic trend analysis, demonstrating how historical data can be transformed into actionable foresight for policymakers and stakeholders in the global market.





