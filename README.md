# Smoking-Detection
## Overview

This project focuses on building a smoking detection system using a meta-learning approach. It utilizes a custom Vision Transformer (ViT) model for feature extraction, addresses the curse of dimensionality problem through Principal Component Analysis (PCA), and employs a tuned XGBoost model for the final classification stage. The entire workflow is organized into four key notebooks: data preparation, ViT feature extraction, XGBoost classification, and model evaluation. The project leverages TensorFlow's Mirrored Strategy for parallel processing, tf.data for efficient data handling, and SHAP for feature explanation.

# Project Results Summary
### Training Results:
- Achieved validation accuracy: 96.11%
- Test accuracy: 96.43%


### Test Results:
- Mean Squared Error: 0.04911
- Weighted F1 Score: 0.951
- Accuracy Score: 95.09%

### Classification Report:
- **Precision, Recall, F1-Score:**
  - For class 'not_smoking':
    - Precision: 0.98
    - Recall: 0.92
    - F1-Score: 0.95
  - For class 'smoking':
    - Precision: 0.92
    - Recall: 0.98
    - F1-Score: 0.95
- **Overall Accuracy:**
  - 95.0%

### demo:
![demo](demo.png)
