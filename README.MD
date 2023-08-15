# OCR CNN Digit Recognition

This project aims to implement a Convolutional Neural Network (CNN) for digit recognition using Optical Character Recognition (OCR) techniques. The CNN model can classify digits from 0 to 9. The code is designed to train the model (`OCR-CNN-Training.py`) and then use the trained model for real-time digit recognition from a camera feed (`OCR-CNN-Test.py`).

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Authors](#authors)
- [References](#references)
- [License](#license)

## Overview

The project consists of two main Python scripts:
- `OCR-CNN-Training.py`: This script trains a CNN model to recognize digits using a dataset of digit images. It uses libraries like OpenCV, Keras, and NumPy for data preprocessing and model creation.
- `OCR-CNN-Test.py`: This script uses a trained model to perform real-time digit recognition using a camera feed. It captures frames, preprocesses them, and feeds them into the model for prediction.

## Prerequisites

- Python 3.x
- Required Python libraries:
  - numpy
  - cv2 (OpenCV)
  - keras
  - matplotlib
  - sklearn
  - tensorflow

## Installation

1. Clone the repository:

2. Install the required libraries:

3. Run the training script to train the CNN model:

4. After training, use the testing script to perform real-time digit recognition:

## Usage

1. Run `OCR-CNN-Training.py` to train the model on a dataset of digit images. The script will save the trained model to a file named `model_trained.p`.

2. Run `OCR-CNN-Test.py` to use the trained model for real-time digit recognition from a camera feed. The script captures frames, preprocesses them, and displays recognized digits with their probabilities on the screen.

## Authors

- Eric Lee

## References

- This project is inspired by MURTAZA'S WORKSHOP's code.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
