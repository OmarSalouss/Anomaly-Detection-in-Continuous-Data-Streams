# Anomaly Detection in Continuous Data Streams

## Project Overview
This project implements a Python script for detecting anomalies in a continuous data stream using two algorithms: **Exponential Moving Average (EMA)** and **Isolation Forest**. It simulates real-time data, identifies unusual patterns, and provides visualization of detected anomalies. Anomaly detection is crucial in various domains, such as finance and network security, where unusual patterns may indicate significant events.

## Python Version
This project is implemented using Python **3.10.12**.

## Technologies Used
- Python 3.10.12
- NumPy
- Plotly
- Scikit-learn

## Features
- **Data Stream Simulation**: Generates data points with seasonal patterns and random anomalies.
- **Anomaly Detection**: Utilizes EMA for real-time anomaly detection and Isolation Forest for batch anomaly detection.
- **Visualization**: Displays the data stream and detected anomalies in real-time using Plotly.

## Installation
To run this project, you will need to install the required libraries. You can use the following command to install them:

```bash
pip install -r requirements.txt
