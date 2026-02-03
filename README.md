# Time Series Analysis and Forecasting with R

## Project Overview
This project focuses on the analysis and forecasting of a univariate time series (*dataset_08*) using R.  
The work was developed as part of a university assignment and implemented in R Markdown to ensure reproducibility and clarity of the analytical process.

The analysis follows a **standard and general workflow** for time series analysis and can be applied to different datasets with minimal modifications.

## Objectives
- Assess the stationarity of the time series  
- Perform data cleaning and exploratory data analysis  
- Transform the series into a stationary process  
- Estimate and compare predictive models  
- Produce point and interval forecasts  

## Project Structure
- `dataset_08.csv` : raw time series data 
- `pw_serie_storiche.Rmd`   : main R Markdown file containing the analysis  
- `pw_serie_storiche.html`  : rendered output  
- `README.md`      : project description  

## Methodology
The analysis begins with exploratory data analysis, including graphical inspection, descriptive statistics, and autocorrelation analysis.  
Stationarity is assessed and, when necessary, achieved through appropriate transformations.  
Different modeling approaches are then estimated and compared.  
Finally, the selected model is used to generate point and interval forecasts.

## Tools and Libraries
- R  
- R Markdown  
- astsa  
- fBasics  
- forecast  
- ggplot2  
- lubridate  
- tseries  
- urca  

## Results
The final model provides satisfactory predictive performance and highlights the main dynamics of the underlying time series.  
Forecasts are presented together with confidence intervals.

## How to Run
1. Clone the repository  
2. Open the `.Rmd` file in RStudio  
3. Install the required packages  
4. Knit the document to HTML  

## Notes
This project was developed for academic purposes.
