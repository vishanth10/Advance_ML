Autoencoder Architecture (architecture.json)​(architecture)
Type: Sequential model.
Layers:
InputLayer: Defines the input shape as [None, 784] (flat vector of size 784).
Dense (Encoder): Reduces dimensions to 260 using the GELU activation, effectively compressing the input.
BatchNormalization: Normalizes the output to improve training stability.
Dense (Decoder): Expands the reduced representation back to the original dimension (784) with a sigmoid activation for reconstruction.
Purpose: The model encodes input data to a lower-dimensional space and then reconstructs it to remove noise or reconstruct data.
