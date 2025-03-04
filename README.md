# ImageFoodClassifier

This repository contains a machine learning project for classifying food images into three categories: **Meal**, **Dessert**, and **Drink**. The project leverages TensorFlow, with a preference for GPU acceleration to improve training and inference performance.

## Features
- Classifies food images into three classes: Meal, Dessert, and Drink.
- Built using TensorFlow for seamless development and scalability.
- Supports both CPU and GPU environments for better performance.

## Installation

To get started with this project, follow the steps below:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Leosce/ImageFoodClassifier
   cd ImageFoodClassifier
   ```

2. **Create a virtual environment** (optional but recommended):
   ```bash
   python -m venv env
   source env/bin/activate  # For Linux/Mac
   env\Scripts\activate     # For Windows
   ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Ensure TensorFlow is configured to use GPU** (if available):
   - Install [CUDA Toolkit](https://developer.nvidia.com/cuda-toolkit) and [cuDNN](https://developer.nvidia.com/cudnn) as per your GPU specifications.
   - Verify TensorFlow GPU setup:
     ```python
     import tensorflow as tf
     print("GPU available:", tf.config.list_physical_devices('GPU'))
     ```

## Usage
   
1. **Run the notebook**:
2. **Evaluate or Test on available data (or any labeled data)**:
3. **Classify a New Image**:
4. **Saving the model for later use**

## Requirements
- Python 3.7+
- TensorFlow (preferably with GPU support)
- CUDA and cuDNN (if using GPU)
- Other dependencies listed in `requirements.txt`.

## Contributing
Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request. 

## License
This project is licensed under the MIT License.
