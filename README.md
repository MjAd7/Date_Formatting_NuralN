This project demonstrates the use of an LSTM neural network to standardize dates written in various formats into a single, consistent format (e.g., YYYY-MM-DD). The model takes date strings with different structures (e.g., "March 1, 1994", "12/08/77", "29-Nov-2018") and transforms them into a unified format.
We will build and compare the performance of three models:

Model 1: Two stacked LSTM layers.
Model 2: A single LSTM layer.
Model 3: A Bidirectional LSTM layer.
By comparing these models, we aim to observe how the number of LSTM layers and bidirectional processing affect model performance.
