# CIFAR-10-Image-Classifier

Welcome to the CIFAR-10 Image Classifier. This project was created as part of a Bootcamp for the Computer Vision Team of the University of Waterloo Aerial Robotics Group.

# Languages, Libraries and Frameworks used:
- Python
- Tensorflow/Keras
- NumPy
- MatPlotLib

# Program Structure:
- Data preprocessing [Numpy]: Compiling all training batches into one NumPy array
- Model Architecture and Training [Tensorflow/Keras]:
  - 4 Sets of VGG Blocks
    - 1 Convolutional Layer
    - 1 Max Pooling Layer
  - Output Layers, which utilizes:
    - Dropouts to prevent overfitting
    - The Softmax activation function for the final layer to display probability of of the image being from either one of the CIFAR-10 classes
- Model Accuracy Visualization [MatPlotLib]: Displayed model accuracy across all Epochs
