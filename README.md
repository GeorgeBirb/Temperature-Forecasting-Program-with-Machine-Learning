# Weather Forecasting Program with Machine Learning

This repository contains a Python program for weather forecasting using machine learning. The program utilizes linear regression to predict the temperature for the next hour based on humidity, pressure, and the current hour.

## Table of Contents

- [Getting Started](#getting-started)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [API Key](#api-key)
- [Data Source](#data-source)
- [File Descriptions](#file-descriptions)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Before running the program, make sure you have the following installed:

- Python (version 3.7 or higher)
- Required Python packages (install using `pip install -r requirements.txt`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/.....
   ```

2. Navigate to the project directory:

   ```bash
   cd weather-forecast
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Obtain an API key from [Visual Crossing Weather Data](https://www.visualcrossing.com/weather/weather-data-services#/login).

2. Replace `'YOUR_KEY'` in the API call with your obtained key in the script.

3. Run the program:

   ```bash
   python weather_forecast.py
   ```

4. Follow the prompts to input humidity and pressure for temperature forecasting.

## API Key

The program requires an API key to fetch weather data. Obtain a free key from [Visual Crossing Weather Data](https://www.visualcrossing.com/weather/weather-data-services#/login) and replace `'YOUR_KEY'` in the API call.

## Data Source

The weather data is fetched from the [Visual Crossing Weather Data API](https://www.visualcrossing.com/weather/weather-data-services).

## File Descriptions

- `weather_forecast.py`: The main Python script for weather forecasting.
- `model.pickle`: Serialized trained linear regression model.
- `03-ΘΕ-02-ΥΕ-02-weather-data-01-02.csv`: Original weather data CSV.
- `03-ΘΕ-02-ΥΕ-02-weather-data-patras-01-02.csv`: Processed weather data CSV.

## Dependencies

- pandas
- matplotlib
- scikit-learn
- numpy
- pickle
- requests

Install dependencies using:

```bash
pip install -r requirements.txt
```

## Contributing

Contributions are welcome. Please open an issue to discuss potential changes or improvements.
