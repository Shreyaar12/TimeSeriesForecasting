# Air Quality Forecasting Project for ITO, New Delhi

## Overview
This project aims to forecast air quality, specifically predicting PM2.5 levels, using LSTM models and exploring zero-shot learning with Llama for time-series prediction. The project utilizes two years of raw air quality data from ITO(site 117), New Delhi, sourced from the Central Pollution Control Board (CPCB). Through a series of data preprocessing steps, the project prepares this raw data for time-series forecasting, culminating in 24-hour ahead predictions.

## Data Source
The dataset comprises raw air quality measurements from ITO, New Delhi, including pollutants such as PM2.5, PM10, NO2, and CO, collected over two years. This data serves as the foundation for our forecasting model.

## Methodology
- **Data Preprocessing**: Cleaning and normalizing the raw CPCB data to make it suitable for modeling.
- **LSTM Model**: Training an LSTM model on the preprocessed data for time-series forecasting.
- **Zero-Shot Learning**: Using GEMMA:7B and Lag-Llama models for zero-shot learning on time-series data.
- **Prediction**: Employing the trained models to predict PM2.5 levels for the next 24 hours.

## Dependencies
- Python 3.x
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

To install the necessary libraries, you can use the following command:
```bash
pip install tensorflow keras pandas numpy matplotlib scikit-learn
```

## Setup and Usage
1. Clone this repository to your local machine.
2. Ensure you have all the required dependencies installed.
3. Navigate to the repository directory and start Jupyter Notebook or JupyterLab.
4. Open and run the provided Jupyter notebooks in the following order:
   - `Time_Series_using_LSTM.ipynb` for the LSTM model training and prediction.
   - `TimeSeries_Lag_Llama_Demo.ipynb` and `TimeSeriesForecasting_Gemma7B.ipynb` for zero-shot learning demonstrations.
5. Review the notebooks for detailed steps on data preprocessing, model training, and prediction.


## Repository Structure
- `Time_Series_using_LSTM.ipynb`: Jupyter notebook detailing the LSTM model training and forecasting.
- `TimeSeries_Lag_Llama_Demo.ipynb`: Notebook demonstrating zero-shot learning with the Llama model for time-series analysis.
- `TimeSeriesForecasting_Gemma7B.ipynb`: Notebook illustrating time-series forecasting with Gemma.
- `2022+2023.csv` : Dataset

## Getting Started
To start using this project:
1. Clone the repository.
2. Install the dependencies listed above.
3. Explore the Jupyter notebooks to understand the preprocessing steps, model training, and prediction processes.

## Usage
1. **Data Preprocessing**: Follow the steps in `Time_Series_using_LSTM.ipynb` to clean and preprocess the raw CPCB data.
2. **Model Training and Forecasting**: Execute the cells in `Time_Series_using_LSTM.ipynb` to train the LSTM model and make predictions.
3. **Zero-Shot Learning Exploration**: Use `TimeSeries_Lag_Llama_Demo.ipynb` and `TimeSeriesForecasting_Gemma7B.ipynb` to explore advanced forecasting techniques.

## Contributing
Contributions to this project are welcome. Please fork the repository, make your changes, and submit a pull request.

## License
This project is open-sourced under the MIT License.

## Acknowledgments
This project utilizes data provided by the Central Pollution Control Board (CPCB), New Delhi. The implementation of LSTM models and exploration of zero-shot learning with GEMMA:7B and Lag-Llama would not have been possible without the contributions from the open-source community and the developers behind these advanced modeling techniques.

## Contact
For questions or feedback regarding this project, please contact shreyarajpal6@gmail.com or drop a message at https://www.projectsbyshr.in/


