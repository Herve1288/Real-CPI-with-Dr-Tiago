CPI Forecasting and Analysis
This project performs time series analysis and forecasting of the Consumer Price Index (CPI) using R. It includes data cleaning, exploratory data analysis, ARIMA modeling, and an interactive Shiny dashboard for forecasting.

Overview
In this project, we:

Load and Clean Data: Import the CPI dataset, convert dates, and clean numeric columns.
Exploratory Analysis: Plot CPI over time and analyze correlations among variables.
Stationarity Tests: Use differencing and the Augmented Dickey-Fuller (ADF) test to assess stationarity.
ARIMA Modeling: Examine ACF/PACF plots to identify model orders, fit several ARIMA and ARIMAX models, and select the best model based on AIC/BIC criteria.
Forecasting: Generate and visualize forecasts for future CPI values.
Interactive Dashboard: Provide a Shiny app for users to upload their data, choose model parameters, and view forecast results interactively.
Files Included
README.Rmd: The R Markdown file containing the full analysis and code.
README.md: This rendered file for GitHub.
data1.csv: Sample dataset used for the analysis (update the file path as needed).
Shiny App Code: The code for an interactive dashboard that allows dynamic forecasting and data exploration.
Requirements
To run this project, you need R (and RStudio is recommended) along with the following packages:

tseries
forecast
tidyverse
ggplot2
ggcorrplot
shiny
readr
DT
You can install these packages using:

r
Copy
install.packages(c("tseries", "forecast", "tidyverse", "ggplot2", "ggcorrplot", "shiny", "readr", "DT"))
How to Run the Analysis
Open the Project:
Open the project folder in RStudio.
Knit the R Markdown File:
Open README.Rmd and click the Knit button. This will generate an HTML (or PDF/Word) document that includes all analysis outputs, plots, and code.
Review the Outputs:
Examine the data summaries, ACF/PACF plots, model diagnostics, and forecasts generated in the document.
Running the Shiny Dashboard
For an interactive experience:

Launch the Shiny App:
Open the Shiny app file provided in the project.
Click Run App in RStudio.
Use the Dashboard:
Upload your CSV file (formatted similarly to data1.csv).
Choose the forecasting model type (ARIMA or ARIMAX) and specify the number of months to forecast.
Click Run Forecast to generate interactive plots and a forecast table.
Download forecast results as a CSV if needed.
Future Enhancements
Possible improvements for this project include:

Adding more external regressors (e.g., GDP, M2, Inflation Rates).
Refining the ARIMA model selection process.
Extending the forecast horizon.
Enhancing the Shiny dashboard interface and functionality.
Acknowledgments
This project was developed by Christian for educational and forecasting purposes. Feel free to fork the repository, suggest improvements, or open issues if you have any questions or feedback.
