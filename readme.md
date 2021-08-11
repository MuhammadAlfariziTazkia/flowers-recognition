# Flowers Recognition
Classification Flowers into 5 category (Daisy, Dandelion, Rose, Sunflower, Tulip)

## Model Structure
- 16 Unit Convolutional 2D
- MaxPooling2D
- 31 Unit Convolutional 2D
- MaxPooling2D
- 64 Unit Convolutional 2D
- MaxPooling2D
- Flatten
- 256 Unit Dense
- Dropout: 0.2
- 512 Unit Dense
- 5 Unit Dense

## Model Accuracy (for 10 epochs)
- Training accuracy: 70.63 %
- Validation accuracy: 73.29 %

