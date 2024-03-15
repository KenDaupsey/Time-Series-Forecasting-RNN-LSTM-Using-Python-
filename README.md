# Time-Series-Forecasting-RNN-LSTM-Using-Python

This repository provides a comprehensive implementation of time series forecasting using Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models in Python. The project focuses on forecasting daily new deaths caused by COVID-19 in the United States for the next 30 days based on historical data.

## Project Overview

Time series forecasting is a crucial task in various domains, including finance, economics, weather prediction, and epidemiology. This project leverages the power of RNN-LSTM models to capture the temporal dependencies and patterns in the COVID-19 daily new deaths data. By training the model on historical data, it can learn the underlying trends and make accurate forecasts for future time points.

## Dataset

The project utilizes the COVID-19 data provided by The New York Times, which is publicly available at `https://raw.githubusercontent.com/nytimes/covid-19-data/master/us.csv`. This dataset contains daily cumulative counts of confirmed cases and deaths due to COVID-19 in the United States.

## Key Features

- **Data Preprocessing**: The project includes necessary data preprocessing steps, such as handling missing values, creating new columns for daily differences in deaths and cases, and preparing the data for the LSTM model.

- **Exploratory Data Analysis**: Visualizations are provided to explore the dataset, including time series plots for different variables and checking for negative values.

- **Data Scaling**: The data is scaled using the `MinMaxScaler` from scikit-learn to ensure that the input features are within a similar range.

- **LSTM Model Training**: The project defines and trains an LSTM model using TensorFlow's Keras library. The model architecture consists of an LSTM layer followed by a Dense layer for producing the output.

- **Time Series Forecasting**: The trained LSTM model is used to forecast daily new deaths for the next 30 days based on the historical data.

- **Visualization**: The forecasted values are plotted alongside the actual data, providing a visual representation of the model's performance.

- **Tabular Output**: A table containing the forecasted new deaths for the next 30 days is generated and displayed.

## Requirements

To run this project, you need to have the following dependencies installed:

- Python 3.x
- pandas
- numpy
- matplotlib
- tensorflow
- scikit-learn

You can install the required packages using pip:

```
pip install pandas numpy matplotlib tensorflow scikit-learn
```

## Usage

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Open the Jupyter Notebook or Python script file.
4. Run the cells or script to execute the code.

The code will perform the steps mentioned in the Key Features section, including data preprocessing, exploratory data analysis, LSTM model training, time series forecasting, visualization, and tabular output generation.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

This project was inspired by the need to provide a practical example of time series forecasting using RNN-LSTM models in Python, with applications in epidemiology and data analysis.
