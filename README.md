# Edge QuantNet

Ultralight Quantized SE-ResNet for Leaf Disease Classification on Edge Devices



Edge QuantNet is a lightweight deep learning model designed for real-time plant disease detection on resource-constrained devices (mobile & IoT).

* Accuracy: 99.72%
* Model Size: 118 KB (INT8)
* Fast, efficient, and deployable on edge hardware


## Architecture

* SE-ResNet (custom lightweight)
* Depthwise separable convolutions
* Residual connections
* SE attention modules



# Pipeline

1. Preprocessing (resize 64×64, normalization, augmentation)
2. Model training (Adam, 50 epochs)
3. INT8 quantization for edge deployment



# Requirements

TensorFlow, NumPy, Scikit-learn, Matplotlib



#📌 Use Cases

* Smart agriculture
* Edge AI
* Offline disease detection

Hossain et al., *Edge QuantNet*, ICCCI 2026
