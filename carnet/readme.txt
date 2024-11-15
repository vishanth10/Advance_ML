ResNet Model (resnet_model_model-1.json)​(resnet_model_model-1)
Type: Functional API.
Key Components:
InputLayer: Input images of shape [None, 228, 228, 3].
Normalization: Normalizes images using predefined mean and variance values.
ConvNext Backbone: Includes multiple convolutional blocks with depth-wise separable convolutions, GELU activations, and layer normalization.
LayerScale: Custom layer for scaling output features.
Add: Implements residual connections for better gradient flow.
Purpose: Extract complex features from images using a deep convolutional network.
4. ConvNext Model (convnext_model_model-1.json)​(convnext_model_model-1)
Type: Functional API similar to ResNet.
Key Components:
InputLayer: Accepts input images with the same dimensions as ResNet.
Normalization: Preprocessing layer to normalize the input.
ConvNext Backbone: Contains convolutional blocks with a focus on efficiency and accuracy.
Residual Connections: Enhances feature propagation.
Purpose: Provides a robust backbone for image feature extraction with efficiency in mind.
