# Prediction Model for the Occupancy of Flights and Sale of Products on Board for Viva Aerobus

May 05, 2024

Dylan Esaú Carreón Martínez, Missael Sepúlveda Ríos, Álvaro Jesús Nieto Gutiérrez & Jorge Ríos Corral

## Description

This project implements two models of supervised learning through the training of a 4-layer and a 5-layer neural network with 2023 flight and sales data from the datasets [`Filghts TEC_Valid.csv`](https://drive.google.com/file/d/1h4GvP8it_wwJsvtJekbBTY8qKGGOUV_s/view) and [`Sales TEC_Valid.csv`](https://drive.google.com/file/d/1Kf0UIkgDdlrkdKBU1IAUpJrYx-0KdK78/view) provided by Viva Aerobus. The 4-layer NN forecasts the occupancy of flights to estimate the number of passengers for flights scheduled for 2024 and part of 2025. The 5-layer NN uses the forecasted occupancy and predicts the number of products sold by category per flight for flights scheduled for 2024 and part of 2025.

This project was developed in Python using Pandas, TensorFlow and Scikit-learn.

## File Contents

- `Datathon Model.ipynb` contains the models of supervised learning for the forecasting of the occupancy of flights and the prediction of sales on board.
- `Passengers Prediction Model Sketch.ipynb` contains a test learning model for the forecasting of the occupancy of flights.
- `test_vuelos.ipynb` contains the exploration, processing and cleansing of the `Sales TEC_Valid.csv` dataset.
- `test_vuelos.ipynb` contains the exploration, processing and cleansing of the `Filghts TEC_Valid.csv` dataset.
