# Flower Species Classifier using CNN

## Dataset Source
https://www.kaggle.com/datasets/l3llff/flowers/data

## Environment setup

```bash
pip install -r requirements.txt
```

##  Model Formats

- **SavedModel**  
  The standard TensorFlow folder format that stores the complete model graph and weights.
- **TFLite**  
  A single `.tflite` file optimized for on-device inference on mobile or embedded platforms (Android, iOS, Raspberry Pi).
- **TensorFlow.js (TFJS)**  
  A `model.json` file with accompanying binary shards (`*.bin`) to run the model directly in web browsers or Node.js.
