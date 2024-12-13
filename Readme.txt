# Apples vs. Tomatoes Classification using CNN Shallow and Deep

This project explores the use of Convolutional Neural Networks (CNNs) for binary image classification to distinguish between apples and tomatoes. The project evaluates two CNN architectures (shallow and Deep) and analyzes their performance, challenges and outcomes.

## Features
- Shallow Model: A simple CNN with fewer layers to demonstrate the impact of shallow architectures.
- Deep Model: An advanced CNN with more layers and regularization techniques for capturing complex patterns.
- Performance Evaluation: Includes confusion matrices, feature map visualizations and analysis of misclassifications.
- Preprocessing: Data augmentation applied to improve model robustness and generalization.

## Dataset
The dataset consists  images of apples and tomatoes, divided into training, validation and test sets. Images are preprocessed to 100x100 dimensions for consistency.

## Preprocessing
- Data Augmentation: Techniques such as rotation, zoom, and horizontal flipping.
- Normalization: Rescaled pixel values between 0 and 1.

## Models
1. Shallow Model: 
   - 3 convolutional layers with max pooling.
   - Dense layers with dropout regularization.
   - Suitable for low-complexity tasks but risks underfitting.

2. **Deep Model:
   - 5 convolutional layers with batch normalization and dropout.
   - Captures complex patterns but requires more computational resources.
   - Higher accuracy but risks overfitting.

## Results
- **Shallow Model: Achieved moderate accuracy but underfits on complex features.
- **Deep Model: Demonstrated better accuracy by capturing more intricate features. 

## Challenges
- **Shallow Model: Underfitting due to limited depth.
- **Deep Model: Overfitting and higher computational demand.

## Future Work
- Experiment with advanced architectures like ResNet or DenseNet.
- Fine-tune pre-trained models to improve efficiency.
- Address dataset imbalance through augmentation or class weighting.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/username/apples-vs-tomatoes.git
   cd apples-vs-tomatoes
pip install -r requirements.txt
python train.py
Usage
simple_model() or advanced_model() functions to select the desire architecture.
Results include accuracy, confusion matrix and misclassified examples.

Requirements
Python 3.7+
TensorFlow/Keras
Matplotlib
Seaborn
scikit-learn
Project Structure
.
├── apples-vs-tomatoes-cnn.py                # First part is Training script
├── apples-vs-tomatoes-cnn.py                # Model definitions (simple and advanced)
├── data/                    # Dataset directory
├── results/                 # Output results (confusion matrices, feature maps)
├── Report.pdf             # Complete documentation
└── README.md                # Project documentation

License
This project is licensed under the University of hertfordshire.
Author
Developed by Sami ul hassan.
Feel free to customize the project name, structure and links as per your setup!
