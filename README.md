# Cloud Resource Requirement Prediction

## Overview

This project aims to predict the resource requirements (CPU, memory, and disk usage) for cloud servers in the near future using machine learning models. Accurate predictions can help in efficient resource allocation, cost management, and ensuring optimal performance of cloud services.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Features

- Data preprocessing and visualization
- Machine learning model for predicting resource requirements
- Evaluation of model performance
- Plotting correlation heatmaps and other visualizations
- Scalable and modular code structure

## Installation

To set up the project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/Im-Alam/VM-Resource-Analysis.git
    cd VM-Resource-Analysis
    ```

2. Create a virtual environment:
    ```sh
    python -m venv vEnv
    source vEnv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. **Data Preparation**:
   - Place your data file (CSV format) in the `data/` directory.
   - Ensure the data has columns for CPU usage, memory usage, and disk usage.


## Model

The project uses a neural network model implemented with TensorFlow and Keras. The model architecture includes:

- Input layer
- LSTM (Long Short-Term Memory) layers for sequence prediction
- Dense layers for regression
- Dropout layers for regularization

The model is trained to predict future resource usage based on historical data.

## Results

The performance of the model is evaluated using metrics such as Mean Absolute Error (MAE) and accuracy. Visualizations are provided to illustrate the correlation between different resource metrics and to show the model's predictions versus actual values.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request to contribute. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

