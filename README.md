# Lung Cancer Detection using 3D Convolutional Neural Networks

## Overview

This research project presents a computer-aided diagnosis (CAD) system for lung cancer classification using deep learning techniques applied to CT scan images. The primary goal is to develop an accurate and reliable method for early lung cancer detection.

## Key Features

- **Methodology**: 
  - 3D Convolutional Neural Networks (CNN)
  - Hybrid 2D/3D CNN architecture
- **Dataset**: 
  - Kaggle Data Science Bowl 2017 dataset
  - 50 patients sample
  - Additional 61 subjects with cancerous lungs

## Model Architectures

### Classic 3D CNN Model
- 83.2% accuracy
- Multiple 3D convolutional and max pooling layers
- Dropout layers to prevent overfitting

### Combined 2D/3D CNN Model
- 83% accuracy
- Innovative architecture combining 3D and 2D convolutions
- Captures volumetric and 2D spatial features

## Performance Metrics

| Metric | Classic 3D CNN | Combined 2D/3D CNN |
|--------|----------------|---------------------|
| Accuracy | 83.2% | 83% |
| AUC | 0.87 - 0.93 | 0.89 - 0.93 |
| Precision | 0.86 - 0.91 | 0.84 - 0.91 |
| Recall | 0.72 - 0.82 | 0.73 - 0.76 |

## Key Preprocessing Steps

- DICOM image loading and processing
- Hounsfield Unit (HU) scaling
- Slice standardization
- 3D visualization using Marching Cubes algorithm

## Potential Improvements

- Incorporate larger datasets (e.g., LUNA16)
- Explore transfer learning
- Implement advanced architectures (3D DenseNets, 3D ResNets)
- Integrate hybrid models with attention mechanisms

## Dependencies

- Python
- NumPy
- OpenCV
- Pydicom
- TensorFlow/Keras
- Scikit-learn

## Installation

```bash
# Clone the repository
git clone https://github.com/amine-sabbahi/CNN3D-LungCancerDetection.git

# Install required dependencies
pip install -r requirements.txt
```

# Collaborators
- [Aymane Mahri](https://github.com/AymaneM21)
- [Mohammed Amine Sabbahi](https://github.com/amine-sabbahi/)