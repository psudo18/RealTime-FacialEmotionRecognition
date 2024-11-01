# Real-Time Facial Emotion Recognition

Welcome to the **Real-Time Facial Emotion Recognition** project! This project aims to develop a deep learning model to classify facial emotions in real-time using a Convolutional Neural Network (CNN). The project has been implemented in Python and is designed to run on Google Colab.

## Table of Contents

- [Project Structure](#project-structure)
- [Installation](#installation)
- [Requirements](#requirements)
- [Usage](#usage)
  - [Training the Model](#training-the-model)
  - [Real-Time Prediction on Google Colab](#real-time-prediction-on-google-colab)
  - [Real-Time Prediction (Local System - Coming Soon)](#real-time-prediction-local-system---coming-soon)
- [Results](#results)
- [License](#license)
- [Contributing](#contributing)

## Project Structure

This repository contains the following files:

- **FacialEmotionRecognition.ipynb**: This Jupyter notebook is dedicated to model development, including:
  - Preprocessing the data.
  - Building a CNN model architecture.
  - Training the model on a dataset.
  - Saving the trained model as `model.keras`.
  
- **RealTimePredictions.ipynb**: This Jupyter notebook performs real-time emotion prediction. It is currently configured for use with Google Colab, enabling live emotion detection with webcam input.

- **model.keras**: This file contains the trained model with an accuracy of 60%, ready for inference.

- **requirements.txt**: A file listing the necessary Python packages for the project without version constraints.

> **Note**: A future update will include a real-time prediction file compatible with local systems.

## Installation

To get started, clone the repository:

```bash
git clone https://github.com/psudo18/RealTime-FacialEmotionRecognition.git
```

Navigate to the project directory:

```bash
cd RealTime-FacialEmotionRecognition
```

You can install the required packages by running:

```bash
pip install -r requirements.txt
```

## Usage

### Training the Model

The `FacialEmotionRecognition.ipynb` notebook walks through the process of training the model. This file must be run in a Jupyter notebook environment, such as Google Colab.

   1. Open the notebook in Google Colab.
   2. Upload your dataset (if necessary).
   3. Run the cells sequentially to preprocess data, build the model, and train it.
   4. The trained model will be saved as `model.keras`.

### Real-Time Prediction on Google Colab

To test the model with live webcam input on Google Colab:

   1. Ensure you have uploaded the `model.keras` file to your Colab environment.
   2. Open and run `RealTimePredictions.ipynb`.
   3. Follow the prompts to allow access to your webcam.

### Real-Time Prediction (Local System - Coming Soon)

A local system-compatible version of real-time prediction will be added soon. Stay tuned for updates!

## Results

The current model achieves **64% accuracy** on the test set. Future enhancements may improve this result through model optimization and additional training data.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to report issues, feel free to open issues or submit pull requests.
