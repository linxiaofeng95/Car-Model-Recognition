# Car Model Recognition

A comparative study of deep learning models for vehicle brand classification using the Stanford Cars dataset.

## Overview

This project compares three different CNN architectures for classifying car brands from images:
- **Custom CNN** - A lightweight architecture built from scratch
- **MobileNetV2** - Efficient model optimized for mobile devices
- **EfficientNetB0** - State-of-the-art efficient architecture

### Dataset
- **Source:** Stanford Cars Dataset
- **Fine-grained Classes:** 196 car models
- **Brand Classes:** 49 car manufacturers
- **Image Size:** 224×224 pixels
- **Batch Size:** 32
- **Training Epochs:** 30

## Features

✓ Data augmentation (flip, brightness, contrast)  
✓ Transfer learning with pre-trained weights  
✓ Model comparison and performance evaluation  
✓ Classification metrics (Precision, Recall, F1-Score)  
✓ Confusion matrix visualization  
✓ Early stopping and learning rate reduction  

## Requirements

- TensorFlow/Keras
- scikit-learn
- NumPy
- Pandas
- Matplotlib
- Python 3.7+

## Usage

1. **Prepare the Dataset**
   - Download Stanford Cars Dataset
   - Place training images in `Stanford_Cars_dataset-main/train/`
   - Place test images in `Stanford_Cars_dataset-main/test/`

2. **Run the Notebook**
   ```bash
   jupyter notebook Final.ipynb
   ```

3. **View Results**
   - Model training progress and losses
   - Classification metrics for each architecture
   - Confusion matrices and sample predictions

## Model Performance

The notebook trains and evaluates all three models, comparing:
- Training time and inference speed
- Model size (total and trainable parameters)
- Precision, Recall, and F1-Score (macro and weighted)
- Accuracy on test set

## File Structure

```
Car-Model-Recognition/
├── Final.ipynb          # Main analysis notebook
└── README.md            # This file
```

## Author

Created on February 19, 2026

## License

Dataset: Stanford Cars Dataset (Academic use)
