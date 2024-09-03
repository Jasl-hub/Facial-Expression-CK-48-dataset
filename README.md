# Facial-Expression CK+48
# Image Classification Project

This repository contains an image classification project using a Convolutional Neural Network (CNN) implemented with Keras. The project aims to classify images into 5 distinct categories with high accuracy.

## Project Overview

The main objective of this project is to develop a deep learning model capable of accurately classifying images. The model was trained on a dataset of images and evaluated to ensure its effectiveness.

### Key Features
- **Training**: The model is trained to identify and classify images into predefined categories.
- **Evaluation**: The model's performance is assessed on a test dataset.
- **Logging**: Training progress is logged, and the best-performing model is saved for future use.
- **Timing**: Custom callbacks are used to measure and log the time taken for training and testing.

### Results
- **Test Accuracy**: 97.35%
- **Test Loss**: 0.2545
- **Testing Time**: 0.042 seconds

## Usage

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Jasl-hub/Facial-Expression-CK-48-dataset.git
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the training script**:
    ```python
    python train.py
    ```

4. **Evaluate the model**:
    ```python
    python evaluate.py
    ```

## Files in the Repository

- **train.py**: Script to train the CNN model.
- **evaluate.py**: Script to evaluate the model's performance.
- **model_train_new.csv**: CSV file containing logs of the training process.
- **Best-weights-my_model-{epoch}-{loss}-{acc}.keras**: Model weights saved during training.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
