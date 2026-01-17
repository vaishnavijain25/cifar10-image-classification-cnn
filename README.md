# Image Classification using CIFAR-10 

This project demonstrates image classification using a Convolutional Neural Network (CNN) on the CIFAR-10 dataset.

##  Dataset
- 60,000 color images (32×32)
- 10 classes (airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)
- 50,000 training images
- 10,000 testing images

##  Models Implemented
1. **Base CNN**
   - Conv2D + MaxPooling
   - Fully Connected ANN
   - Overfitting observed

2. **Improved CNN**
   - Batch Normalization
   - Dropout
   - L2 Regularization
   - Reduced overfitting & better generalization

##  Results
| Model | Train Accuracy | Validation Accuracy |
|------|---------------|---------------------|
| Base CNN | ~91% | ~64% |
| Regularized CNN | ~77% | ~73% |

##  Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

