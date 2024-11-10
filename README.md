
# California Housing Prices Prediction

## Project Overview
This Jupyter notebook provides a comprehensive machine learning approach to predicting housing prices in California. The dataset originates from the StatLib repository, which is based on data from the 1990 California census. We tackle the challenge by performing extensive data analysis, preprocessing, and model optimization to forecast median housing prices at the district level.

## Table of Contents
1. **Introduction**
   - Purpose of the Project
   - Data Source and Key Features
2. **Data Exploration**
   - Descriptive Statistics
   - Missing Values Handling
3. **Data Visualization**
   - Distribution of Key Features
   - Geographical Price Mapping
   - Correlation Heatmaps
4. **Feature Engineering**
   - Attribute Combinations
   - Impact on Model Performance
5. **Data Preprocessing**
   - Feature Scaling Techniques
   - Transformation Pipelines
6. **Model Selection and Tuning**
   - Model Selection Rationale
   - Grid Search Optimization
   - Randomized Search Benefits
7. **Evaluation and Conclusions**
   - Model Performance Metrics
   - Discussion of Results
   - Limitations and Future Work

## Getting Started

### Prerequisites
To run this notebook effectively, you need:
- Python 3.7+
- Jupyter Notebook or JupyterLab
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

### Installation
Install the required Python packages using pip:
```bash
pip install notebook pandas numpy matplotlib seaborn scikit-learn
```

### Running the Notebook
Clone the repository and navigate to the project directory. Start Jupyter Notebook and open the `california-housing-prices-ml.ipynb` file:
```bash
git clone https://github.com/ompac/California-Housing-Prices-ML
cd California-Housing-Prices-ML
jupyter notebook
```

## Detailed Explanation

### Data Exploration and Visualization
The notebook begins with a thorough exploratory data analysis (EDA) to understand the underlying patterns and anomalies in the data. Visualizations include histograms, scatter plots, and box plots that highlight the distribution and relationships of the features.

### Feature Engineering and Preprocessing
We create new features by combining existing attributes to provide more predictive power to the models. Standard preprocessing steps such as scaling and encoding are automated via a pipeline, ensuring that transformations are applied consistently across training and testing datasets.

### Model Building and Evaluation
Multiple regression models are tested, including linear regression, decision trees, and ensemble methods. The models are fine-tuned using both Grid Search and Randomized Search to optimize their parameters. Performance is assessed using RMSE (Root Mean Squared Error), with results discussed in detail.

## Contributions
Contributions are welcome, especially in the areas of model improvement, feature engineering, and data visualization. Please fork the repository and submit pull requests with your suggested changes.

## License
This project is made available under the MIT License, which allows for modification, distribution, and private or commercial use.

## Contact
For questions and feedback, please reach out to [omarrabiesarhan@gmail.com](mailto:omarrabiesarhan@gmail.com).
