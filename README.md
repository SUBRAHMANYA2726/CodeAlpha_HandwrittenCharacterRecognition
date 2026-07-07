# CodeAlpha Handwritten Character Recognition

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-FF6F00?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-3.x-D00000)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8?logo=opencv)
![NumPy](https://img.shields.io/badge/NumPy-1.26%2B-013243?logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?logo=pandas)
![Scikit-learn](https://img.shields.io/badge/Scikit-learn-1.4%2B-F7931E?logo=scikit-learn)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-181717?logo=github)
![MIT License](https://img.shields.io/badge/License-MIT-green.svg)
![Stars](https://img.shields.io/badge/stars-0-blue)
![Forks](https://img.shields.io/badge/forks-0-blue)
![Last Commit](https://img.shields.io/badge/last%20commit-2026--07--07-brightgreen)
![Issues](https://img.shields.io/badge/issues-open-yellow)
![Pull Requests](https://img.shields.io/badge/PRs-welcome-brightgreen)

## Project Description

This repository contains a complete end-to-end machine learning project for handwritten character recognition using the MNIST dataset. The project demonstrates data preprocessing, exploratory data analysis, training deep learning models, evaluation, and result visualization in a professional and portfolio-ready format.

## Objectives

- Build a robust handwritten digit recognition system.
- Compare multiple deep learning approaches.
- Produce clear documentation and reusable project assets.
- Present the work in a GitHub-ready format for portfolio and submission use.

## Features

- CNN-based image classification workflow
- Exploratory data analysis with visualizations
- Training and evaluation pipelines
- Performance comparison across baseline models
- Export-ready metrics and model assets
- Professional repository structure and docs

## Dataset Information

- Dataset: MNIST Handwritten Digits
- Source: TensorFlow/Keras built-in dataset
- Classes: 10 digits from 0 to 9
- Image Size: 28x28 grayscale

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- GitHub

## Libraries Used

- tensorflow
- keras
- numpy
- pandas
- matplotlib
- seaborn
- opencv-python
- scikit-learn
- jupyter

## Deep Learning Models Used

- Artificial Neural Network (ANN)
- Basic Convolutional Neural Network (CNN)

## Workflow Diagram

1. Load dataset
2. Preprocess images
3. Perform EDA
4. Train baseline models
5. Evaluate accuracy and loss
6. Save metrics and model artifacts

## Model Architecture

The CNN architecture includes convolutional layers, pooling layers, flattening, and dense output layers for 10-class classification.

## Data Preprocessing

- Pixel normalization to the range 0 to 1
- Reshaping to 28x28x1 format
- One-hot encoding of labels

## EDA

- Random sample visualization
- Class distribution plotting
- Heatmaps for average images and std deviation
- PCA projection and edge detection analysis

## Training

The model is trained using categorical cross-entropy and the Adam optimizer with validation data.

## Evaluation

The project evaluates accuracy, loss, confusion matrices, and classification reports.

## Model Comparison

The repository includes a comparison of baseline ANN and CNN models along with saved metrics.

## Performance Metrics

- Accuracy
- Loss
- Validation performance
- Classification report

## Results

The trained CNN model demonstrates strong handwritten digit recognition performance and is suitable for portfolio and academic presentation.

## Screenshots

Screenshots and placeholders are stored in the [screenshots](screenshots) folder.

## Prediction Examples

Prediction outputs and examples can be found in [outputs/predictions](outputs/predictions).

## Folder Structure

See [PROJECT_STRUCTURE.md](PROJECT_STRUCTURE.md).

## Installation

```bash
git clone https://github.com/SUBRAHMANYA2726/CodeAlpha_HandwrittenCharacterRecognition.git
cd CodeAlpha_HandwrittenCharacterRecognition
pip install -r requirements.txt
```

## Requirements

Install the required libraries using:

```bash
pip install -r requirements.txt
```

## How to Run

```bash
jupyter notebook notebooks/CodeAlpha_HandwrittenCharacterRecognition.ipynb
```

## Output

- Training plots in [outputs/graphs](outputs/graphs)
- Metrics in [outputs/metrics](outputs/metrics)
- Reports in [outputs/reports](outputs/reports)
- Saved model in [saved_models](saved_models)

## Future Improvements

- Add data augmentation
- Experiment with transfer learning
- Deploy the model as a web app
- Add Grad-CAM visualization

## Acknowledgements

- TensorFlow and Keras for deep learning support
- MNIST dataset contributors
- CodeAlpha for project guidance

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).

## Author Information

- Author: Subrahmanya
- GitHub: https://github.com/SUBRAHMANYA2726
- LinkedIn: https://www.linkedin.com/in/your-profile
- Email: your.email@example.com

## Repository Link

https://github.com/SUBRAHMANYA2726/CodeAlpha_HandwrittenCharacterRecognition
