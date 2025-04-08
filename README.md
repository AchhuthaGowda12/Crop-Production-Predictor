# 🌾 Crop Production Predictor

A machine learning-powered Streamlit application that predicts crop production based on environmental and agricultural factors.

## Features

- **Data Exploration**: Analyze and visualize crop production data
- **Production Prediction**: Estimate crop yields based on various parameters
- **Results Dashboard**: Track and compare predictions with interactive visualizations
- **Recommendation System**: Get insights on optimal farming conditions

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/AchhuthaGowda12/Crop-Production-Predictor.git
   cd crop-production-predictor
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Place your dataset file named "Crop Prediction dataset.csv" in the root directory or in a "data" folder

2. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

3. Access the app in your web browser at `http://localhost:8501`

## Data Format

The application expects a CSV file with the following columns:
- State_Name: State where crops are grown
- District_Name: District within the state
- Season: Growing season (Kharif, Rabi, etc.)
- Crop: Type of crop
- Crop_Year: Year of cultivation
- Temperature: Average temperature in °C
- Humidity: Average humidity percentage
- Soil_Moisture: Soil moisture percentage
- Area: Cultivated area in hectares
- Production: Crop production in tons (target variable)

## Deployment

This application can be deployed on Streamlit Cloud:

1. Push your code to GitHub
2. Sign in to [Streamlit Cloud](https://streamlit.io/cloud)
3. Deploy your app by connecting to your GitHub repository
