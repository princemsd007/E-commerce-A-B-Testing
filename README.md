# E-commerce A/B Testing Analysis

## Project Overview

This project simulates and analyzes an A/B test for an e-commerce website. It demonstrates advanced statistical analysis techniques, data visualization, and machine learning applications in the context of e-commerce optimization.

## Features

- Simulated e-commerce dataset generation
- A/B testing using t-test and z-test
- One-way ANOVA for device comparison
- Logistic regression for conversion prediction
- Comprehensive data visualization

## Requirements

- Python 3.7+
- NumPy
- Pandas
- Matplotlib
- Seaborn
- SciPy
- Statsmodels
- Scikit-learn

You can install the required packages using:## Project Structure pip install numpy pandas matplotlib seaborn scipy statsmodels scikit-learn


- `ecommerce_ab_test.py`: Main script containing all the functions and analysis
- `README.md`: This file, containing project information and instructions

## Usage

1. Clone the repository: git clone https://github.com/princemsd007/E-commerce-A-B-Testing.git

    cd ecommerce-ab-testing

2. Run the script: python ecommerce_ab_test.py

## Key Components

1. **Data Generation**: Simulates e-commerce data including visitor information, device types, and conversion rates.

2. **Statistical Analysis**:
- A/B testing using t-test and z-test
- One-way ANOVA to compare conversion rates across devices
- Tukey's HSD test for multiple comparisons

3. **Data Visualization**:
- Conversion rates by group and device
- Distribution of time spent and pages visited

4. **Machine Learning**:
- Logistic regression model to predict conversions
- Feature importance analysis

## Results

The script outputs:
- Summary statistics of the generated data
- Results of A/B tests and ANOVA
- Visualizations of key metrics
- Logistic regression model performance and feature importances

## Extending the Project

You can extend this project by:
- Adding more features to the simulated dataset
- Implementing more advanced machine learning models
- Integrating with real data sources (e.g., Google Analytics API)
- Adding time series analysis for trend detection

## Contributing

Feel free to fork the project, open issues, or submit PRs. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open source and available under the [MIT License](LICENSE).
