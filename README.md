# Surface Crack Detection using ResNet18

## Overview
This project uses transfer learning with a pretrained ResNet18 convolutional neural network (CNN) for binary classification of industrial surface crack images.

The model classifies images into:
- Positive (Crack)
- Negative (No Crack)

The goal is to demonstrate an end-to-end deep learning workflow for industrial defect detection using PyTorch.

---

## Dataset
Surface Crack Detection dataset containing 40,000 images.

Dataset structure:
```text
imgdata/
├── Positive/
└── Negative/

## Results

### Validation Accuracy
**99.15%**

### Confusion Matrix

| Actual | Predicted Negative | Predicted Positive |
|---|---:|---:|
| Negative | 3979 | 21 |
| Positive | 47 | 3953 |

### Key Observation
The model achieved high validation accuracy with low false negative rate, which is important for industrial defect detection applications.
