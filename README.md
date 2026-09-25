## Flower Images Classification

### Overview

This project focuses on multi-class flower image classification using deep learning. The goal is to classify flower images into five different flower categories.

### Dataset

The dataset contains **5,000 images** belonging to five flower classes:

- Lilly
- Lotus
- Orchid
- Sunflower
- Tulip

The dataset was divided into:

- Training images: 4,000
- Validation images: 1,000

Images were resized to **128 × 128 pixels** with RGB color channels.

### Data Augmentation

The following image augmentation techniques were used:

- Rotation
- Zoom
- Shear
- Horizontal Flip

### Models Used

The following models were trained and evaluated:

- MLP
- CNN
- MobileNetV2
- ResNet50
- EfficientNetB0
- VGG16

Transfer learning and fine-tuning were used with the pretrained deep learning models.

### Validation Accuracy

| Model | Validation Accuracy |
|---|---:|
| MLP | 45.60% |
| CNN | 53.60% |
| MobileNetV2 | 91.00% |
| ResNet50 | 26.00% |
| EfficientNetB0 | 20.00% |
| VGG16 | 80.60% |

### Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Deep Learning
- Convolutional Neural Networks
- Transfer Learning

### Project File

The complete implementation is available in:

`Flower_Images (1).ipynb`

### Dataset Source

The dataset was obtained from Kaggle.

## License

The dataset is listed on Kaggle under **Other (specified in description)**.
