# Fuel Economy Linear Regression Analysis

## Overview

This project analyzes the Auto MPG dataset using linear regression techniques to predict fuel economy (miles per gallon) based on various vehicle characteristics. The analysis explores relationships between fuel efficiency and factors such as weight, horsepower, number of cylinders, and other automotive features.

## Dataset

The project uses the **Auto MPG dataset** which contains information about various car models and their fuel efficiency metrics.

### Features:
- **mpg**: Miles per gallon (target variable)
- **cylinders**: Number of cylinders in the engine
- **displacement**: Engine displacement
- **horsepower**: Engine horsepower
- **weight**: Vehicle weight
- **acceleration**: Time to accelerate from 0-60 mph
- **model year**: Year the car was manufactured
- **origin**: Country of origin (1: USA, 2: Europe, 3: Asia)
- **car name**: Name of the car model

## Project Structure

```
Fuel_Economy_LinRegression/
├── auto-mpg.ipynb          # Main Jupyter notebook with analysis
├── Data/
│   └── auto-mpg.csv        # Dataset file
├── anaconda_projects/      # Anaconda project configuration
└── README.md              # This file
```

## Requirements

To run this project, you'll need the following Python libraries:

- pandas
- numpy
- seaborn
- matplotlib (likely used for visualizations)
- scikit-learn (for linear regression models)

## Installation

1. Clone or download this repository
2. Install required dependencies:
   ```bash
   pip install pandas numpy seaborn matplotlib scikit-learn
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook auto-mpg.ipynb
   ```

## Analysis Overview

The notebook includes:

1. **Data Exploration and Preprocessing**
   - Loading and examining the dataset structure
   - Handling missing values (particularly in the horsepower column)
   - Converting categorical variables to appropriate data types
   - Data cleaning and preparation

2. **Exploratory Data Analysis**
   - Statistical summaries of the data
   - Visualization of relationships between variables
   - Correlation analysis

3. **Linear Regression Modeling**
   - Building predictive models for fuel economy
   - Feature selection and engineering
   - Model evaluation and performance metrics

4. **Results and Insights**
   - Model performance analysis
   - Key factors affecting fuel economy
   - Conclusions and recommendations

## Key Findings

The analysis reveals important relationships between vehicle characteristics and fuel economy, providing insights into factors that most significantly impact miles per gallon performance.

## Usage

1. Open the `auto-mpg.ipynb` notebook in Jupyter
2. Run cells sequentially to reproduce the analysis
3. Modify parameters or add new features as needed
4. The dataset is automatically loaded from the `Data/` directory

## Data Source

The Auto MPG dataset is a classic machine learning dataset commonly used for regression analysis and is available from the UCI Machine Learning Repository.

## Contributing

Feel free to fork this project and submit pull requests for improvements or additional analysis.

## License

This project is for educational and research purposes.
