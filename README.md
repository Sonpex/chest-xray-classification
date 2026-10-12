# Chest X-ray Classification

Deep learning project focused on multi-class classification of chest X-ray images.

## Classes

The models classify chest X-rays into six categories:

- COVID-19
- Emphysema
- Normal
- Bacterial Pneumonia
- Viral Pneumonia
- Tuberculosis

## Methods

The project compares custom CNN architectures with ImageNet-pretrained models and evaluates multiple optimization strategies:

- Custom CNNs
- ResNet50
- DenseNet121
- EfficientNet-B0
- MobileNetV2
- Transfer Learning
- Fine-Tuning
- Data Augmentation
- MixUp
- Test-Time Augmentation
- Model Pruning
- Ensemble Learning

## Results

The best validation-selected ensemble achieved:

- Accuracy: 97.24%
- Macro F1-score: 97.27%
- ROC-AUC: 99.74%

The strongest individual model achieved a Macro F1-score of approximately 95.85%.

## Technologies

Python · PyTorch · torchvision · scikit-learn · pandas · NumPy · matplotlib

## Authors

Oliwia Frączek-Warias  
Kamil Dłubak

## Disclaimer

This project was developed for academic purposes and is not intended for clinical diagnosis.