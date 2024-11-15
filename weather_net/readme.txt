LSTM-based Sequential Model (keras_model.json)​(keras_model)
Type: Sequential model for time-series analysis.
Key Components:
InputLayer: Handles sequential data with input shape [None, 24, 9].
Bidirectional LSTM: Combines forward and backward passes to capture temporal dependencies. Includes:
Forward LSTM: Standard LSTM with 256 units and tanh activation.
Backward LSTM: Similar LSTM with backward processing.
BatchNormalization: Stabilizes intermediate layer outputs.
Dropout: Prevents overfitting.
Purpose: Processes time-series data with bidirectional modeling for improved predictions.
