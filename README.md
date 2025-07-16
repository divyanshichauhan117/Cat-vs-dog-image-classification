# Cat vs Dog Image Classification

A deep learning project that uses Convolutional Neural Networks (CNNs) to classify images of cats and dogs. Built with TensorFlow/Keras and designed to run seamlessly in Google Colab.

##  Features

- **Data Augmentation**: Improves model generalization with rotation, shifting, and flipping
- **Interactive Visualization**: Displays sample images and training progress
- **Smart Training**: Includes early stopping and learning rate reduction
- **Model Evaluation**: Comprehensive testing with visual prediction results

### Core Dependencies
- Python 3.7+
- TensorFlow 2.x
- Keras
- NumPy
- Matplotlib
- Pillow (PIL)
- Requests

##  Dataset

The project uses a flexible dataset approach:

1. **Primary**: Downloads sample images from Wikipedia Commons
2. **Fallback**: TensorFlow's cats_vs_dogs dataset
3. **Synthetic**: Generated colored patterns for demonstration

**Dataset Statistics:**
- Training images: ~80% of available data
- Validation images: ~20% of available data
- Image size: 150x150 pixels
- Classes: 2 (cats and dogs)
  
**Key Components:**
- **Convolutional Layers**: Extract image features
- **Max Pooling**: Reduce spatial dimensions
- **Dropout**: Prevent overfitting
- **Dense Layers**: Final classification
- **Sigmoid Activation**: Binary classification output

##  Code Blocks Overview

| Block | Description | Key Features |
|-------|-------------|--------------|
| 1 | Setup & Libraries | Import dependencies |
| 2 | Dataset Download | Multiple data sources |
| 3 | Data Preprocessing | Augmentation & generators |
| 4 | Visualize Samples | Display dataset images |
| 5 | Build CNN Model | Define architecture |
| 6 | Train Model | Fit with callbacks |
| 7 | Training Plots | Visualize progress |
| 8 | Make Predictions | Test individual images |
| 9 | Visual Results | Display predictions |
| 10 | Evaluate & Save | Final metrics & export |

##  Monitoring Training

The project includes comprehensive monitoring:

- **Real-time Progress**: Training/validation metrics per epoch
- **Visual Graphs**: Accuracy and loss curves
- **Early Stopping**: Prevents overfitting
- **Learning Rate Reduction**: Adapts to training progress
 
##  License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- TensorFlow team for the framework
- Keras for the high-level API
- Wikipedia Commons for sample images
- Google Colab for free GPU access.

Made by **Divyanshi Chauhan**
