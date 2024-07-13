# Efficiency Analysis Of LSTM-Based Earthquake Forecasting For Smart City Resilience

## Overview
This repository contains the code and documentation for our project titled "Efficiency Analysis Of LSTM-Based Earthquake Forecasting For Smart City Resilience: A Time Complexity Perspective." The project focuses on leveraging various Long Short-Term Memory (LSTM) architectures to predict earthquakes, aiming to enhance the resilience of smart cities.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributors](#contributors)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction
In the evolving landscape of urban development, smart cities represent a visionary approach to addressing the complexities of modern living. Our project introduces a novel composite LSTM technique optimized for minimizing prediction time in earthquake forecasting for smart city resilience. Additionally, we explore Bidirectional LSTM (Bi-LSTM), Incremental LSTM, and traditional RNN models to further enrich earthquake prediction capabilities.

## Project Structure
```
.
├── data
│   ├── raw
│   ├── processed
├── models
│   ├── lstm_model.py
│   ├── bilstm_model.py
│   ├── incremental_lstm_model.py
│   ├── rnn_model.py
├── notebooks
│   ├── data_preprocessing.ipynb
│   ├── model_training.ipynb
│   ├── model_evaluation.ipynb
├── results
│   ├── figures
│   ├── tables
├── README.md
└── requirements.txt
```

## Requirements
- Python 3.8+
- TensorFlow
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

You can install the necessary packages using the following command:
```bash
pip install -r requirements.txt
```

## Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/earthquake-forecasting-lstm.git
```
2. Navigate to the project directory:
```bash
cd earthquake-forecasting-lstm
```
3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage
### Data Preprocessing
Run the `data_preprocessing.ipynb` notebook to preprocess the seismic data.

### Model Training
Use the `model_training.ipynb` notebook to train the different LSTM models on the preprocessed data.

### Model Evaluation
Evaluate the performance of the trained models using the `model_evaluation.ipynb` notebook.

## Results
The results of our experiments, including computational complexity and prediction accuracy, are available in the `results` directory. We provide comparative graphs and tables to illustrate the performance of the various models.

## Contributors
- Nannuri Charan Sai (Reg. No.: 225003026, CSE)
- Katakam Pavan Kalyan (Reg. No.: 225003102, CSE)
- Avula Venkata Siva Koti Reddy (Reg. No.: 225003186, CSE)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

