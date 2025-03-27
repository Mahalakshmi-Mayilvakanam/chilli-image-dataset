# AI-Powered Fungal Detection in Dried Chili Using Deep Learning

## Overview
This project focuses on detecting fungal infections in dried chilies using deep learning techniques. The primary goal is to automate the identification process, ensuring food safety and quality. The model was trained using three different architectures, with **ResNet** achieving the best accuracy.

## Features
- Automated fungal detection in dried chilies
- Implementation of **CNN, VGG16, and ResNet** architectures
- Optimized for high accuracy and efficiency
- Dataset preprocessing and augmentation techniques applied for improved performance

## Technologies Used
- **Python**
- **TensorFlow / Keras**
- **OpenCV** (for image processing)
- **Matplotlib, Seaborn** (for visualization)

## Model Performance
| Model  | Training Accuracy | Validation Accuracy |
|--------|------------------|--------------------|
| CNN    | 88%              | 80%                |
| VGG16  | 80%              | 60%                |
| ResNet | 91%              | 82%                |

**ResNet** provided the best accuracy and was finalized for deployment.

## Dataset
The dataset consists of images of dried chilies categorized into **fungal-infected** and **non-infected** samples. It underwent preprocessing, including:
- Resizing images to a standard shape
- Data augmentation to enhance model generalization
- Normalization for better convergence

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/ai-fungal-detection.git
   cd ai-fungal-detection
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the training script:
   ```sh
   python train.py
   ```

## Usage
- **To predict a new image:**
  ```sh
  python predict.py --image path/to/image.jpg
  ```

## Results & Analysis
- Achieved high accuracy with **ResNet**, proving its effectiveness for fungal detection.
- Data augmentation helped in handling limited dataset challenges.
- Future improvements include real-time detection using a mobile or web-based interface.
