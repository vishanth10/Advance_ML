GAN Architecture (keras_model-4.json)​(keras_model-4)
Type: Functional API.
Key Components:
EfficientNet Backbone: Pretrained model for extracting image features.
Rescaling and Normalization: Ensures input images are scaled correctly.
DepthwiseConv2D and BatchNormalization: Used for efficient feature extraction at various depths.
GlobalAveragePooling2D: Reduces spatial dimensions to a single value per feature map.
Dense Layers: Final classification or embedding layers.
Purpose: Detects fake images by extracting and analyzing features using a lightweight backbone.
