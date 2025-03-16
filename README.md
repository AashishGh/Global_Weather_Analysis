# Global Weather Repository Analysis

## Overview
This project analyzes a comprehensive global weather dataset to identify patterns, trends, and develop predictive models for temperature forecasting. Using various machine learning techniques, the analysis explores temperature distributions across countries, correlations between weather parameters, and precipitation patterns.

## Features
- Exploratory data analysis of global temperature distributions
- Country-specific weather pattern analysis
- Correlation analysis between key weather variables
- Precipitation analysis across different regions
- Time series forecasting using multiple machine learning models:
  - Linear Regression
  - Random Forest
  - Gradient Boosting
  - XGBoost

## Dataset
The analysis uses the Global Weather Repository dataset containing daily weather information for cities worldwide, including:
- Temperature readings (Celsius)
- Humidity levels
- Wind speed
- Precipitation data
- UV index values
- Geographic information

## Requirements
```
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
datetime
```

## Usage
1. Clone the repository
2. Install the required packages: `pip install -r requirements.txt`
3. Open the Jupyter notebook: `jupyter notebook weather_analysis.ipynb`
4. Run all cells in the notebook to reproduce the analysis

## Project Structure
```
├── GlobalWeatherRepository.csv           # Dataset file
├── Global_Weather_Analysis_Report.pdf    # Report document
├── weather_analysis.ipynb                # Main analysis notebook
├── requirements.txt                      # Required packages
├── README.md                             # This file
└── images/                               # Generated visualizations
    ├── temp_distribution.png
    ├── temp_by_country.png
    ├── correlation_matrix.png
    ├── rainfall_distribution.png
    ├── rainfall_by_country.png
    ├── model_comparisons.png
    ├── model_rmse_comparison.png
    └── model_r2_comparison.png
```

## License

MIT License

Copyright (c) 2025 Aashish Ghimire

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

