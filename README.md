# Economic Indicators Data Analysis

## Overview

This repository contains the code and data for analyzing economic indicators using the Federal Reserve Economic Data (FRED) API. The analysis focuses on three key indicators: GDP Growth Rate, Unemployment Rate, and S&P 500 index.

## Contents

- [Background](#background)
- [Data](#data)
- [Analysis](#analysis)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Folder Structure](#folder-structure)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Background

Understanding economic trends and relationships between different indicators is crucial for making informed decisions in finance, policy-making, and investment strategies. This project utilizes data from the FRED API to analyze and visualize trends in GDP growth, unemployment rates, and stock market performance over time.

## Data

The data used in this analysis is retrieved from the FRED API, which provides access to a wide range of economic data from various sources. Three main indicators are analyzed:

- GDP Growth Rate: Measures the percentage change in real gross domestic product from one period to another.
- Unemployment Rate: Represents the percentage of the labor force that is unemployed and actively seeking employment.
- S&P 500 Index: A stock market index that measures the performance of 500 large companies listed on stock exchanges in the United States.

## Analysis

The analysis involves the following steps:

1. Data Retrieval: Downloading economic indicator data from the FRED API.
2. Data Preprocessing: Cleaning, resampling, and handling missing values in the dataset.
3. Exploratory Data Analysis: Calculating summary statistics, identifying trends, and visualizing the data using Python libraries such as pandas, matplotlib, and Plotly Express.
4. Key Insights and Recommendations: Generating insights and recommendations based on the analysis results.

## Key Insights

- GDP Growth Rate: The GDP growth rate fluctuated over the years with notable dips during economic downturns. The overall trend indicates periods of economic expansion and contraction. There was a significant decline during the COVID-19 pandemic period around 2020, reflecting the economic impact of the pandemic.
- Unemployment Rate: The unemployment rate shows an inverse relationship with the GDP growth rate. Higher unemployment rates are observed during economic recessions. There was a sharp increase in the unemployment rate during the COVID-19 pandemic, followed by a gradual recovery.
- S&P 500 Index: The S&P 500 index generally shows an upward trend, reflecting long-term growth in the stock market. Significant volatility can be observed during major economic events, such as the 2020 pandemic, which saw a rapid decline followed by a strong recovery.

## Recommendations

- Economic Policy: Implementing timely fiscal and monetary stimulus measures during economic downturns can help stabilize the economy and reduce unemployment. Job creation programs should be considered to accelerate economic recovery during periods of high unemployment.
- Investment Strategy: Investors should diversify their portfolios to mitigate risks associated with economic volatility. Maintaining a long-term investment perspective can yield substantial returns despite short-term market fluctuations.
- Data Handling: When handling missing data, consider using more sophisticated techniques like linear interpolation to preserve the integrity and trend of the data while minimizing bias.

## Folder Structure
economic-indicators-analysis/
│
├── data/
│ ├── README.md
│ ├── gdp_growth_rate.csv
│ ├── unemployment_rate.csv
│ └── sp500.csv
│
├── notebooks/
│ └── Economic_Indicators_Analysis.ipynb
│
├── README.md
└── requirements.txt


## Dependencies

- Python 3.x
- pandas
- matplotlib
- Plotly Express
- fredapi

Install the required dependencies using `pip install -r requirements.txt`.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your_username/economic-indicators-analysis.git


## Install Dependencies 
cd economic-indicators-analysis
pip install -r requirements.txt

Open and run the Jupyter notebook notebooks/Economic_Indicators_Analysis.ipynb to reproduce the analysis.
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.

Feel free to make any further adjustments to this template to better fit your project's needs!
