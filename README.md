
# Global Export Forecasting (ARIMA vs. Regression, 188 Economies)

This is an empirical, large-scale econometrics project comparing log-linear OLS regression and Auto-ARIMA models across 188 economies for the time range 1960 to 2023 to forecast the exports in 2030.

## Motivation Behind The project

I have always been very interested in different countries of the world and the way their culture and history shape their economy and in turn their exports. Although, I am an economics student and I haven't studied history and geography in a long time, this personal project is an ode to my love for those subjects. The only reason I'm writing this here is because I don't think anyone is ever gonna read this. If you're reading this, thank you! <3 

## Executive Summary and Core Findings 

Linear trend models (OLS) remain a common baseline in macro-forecasting due to simplicity, but they fail to capture structural breaks, business cycles, and non-stationary trends in global trade. This project evaluates whether adaptive time-series models (ARIMA) deliver statistically significant improvements over linear trends, specifically analyzing performance variations across World Bank income brackets.

### Headline Results
1. 89.4% Algorithmic Win Rate: Auto-ARIMA outperformed Log-Linear OLS in 168 out of 188 sovereign economies based on Out-of-Sample (OOS) Mean Absolute Percentage Error (MAPE).

2. Statistical Significance: A paired Wilcoxon signed-rank test on error differences confirms that ARIMA's superior performance is statistically significant (p < 0.001$).

3. Low-Income Volatility Edge: ARIMA’s advantage over OLS is most pronounced in Low-Income economies where structural shocks and high volatility destroy linear assumptions.

4. Top 2030 Export Growth Projections: The highest projected growth rates through 2030 occur in developing economies experiencing recent structural shifts, led by the Democratic Republic of Congo (+224%), Armenia (+189%), Uzbekistan (+183%), Ethiopia (+177%), and Kosovo (+161%). ( Shocking, I know, but the models don't know anything about geopolitics; this answer is strictly based upon what the model predicted according to the most recent trends).

## Methodology

1. Data Preprocessing: Log-transforming raw exports (logY) to stabilize exponential curves and variance. Linear interpolation was applied for minor internal missing values.

2. Stationarity & Model Diagnostics: Augmented Dickey-Fuller (ADF) tests were used to confirm non-stationarity, justifying order differencing. Residual autocorrelation was verified via Ljung-Box diagnostic tests.
3. Walk-Forward Backtesting: Models were evaluated out-of-sample across three chronological cutoffs (2010, 2015, and 2019) using 4-year forecast horizons to compute robust MAPEs without data leakage.




## Current Bugs / Future Improvements Possible

1. Nigeria's R-squared is coming out to be negative infinity.
2. Also, the next phase of this project can include more advanced models like the  ARIMAX, SARIMAX, XGBoost, etc.
3. Another upgrade in this project could be a live simulation of the countries and it's export predictions, the different diagnostics undertaken etc.
## Data Source

World Bank open data for absolute exports of goods and services  per country (current USD).
(https://data.worldbank.org/indicator/NE.EXP.GNFS.CD)
## Visual Representation




## Authors

- [@kanaknath14](https://github.com/kanaknath14)

