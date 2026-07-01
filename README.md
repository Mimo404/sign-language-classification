## Sign Language Classification using Deep Learning

A deep learning project that classifies American Sign Language (ASL) hand gestures using three different neural network approaches:

* Convolutional Neural Network (CNN)
* Multi-Layer Perceptron (MLP)
* Transfer Learning with MobileNetV2

(The goal of this project is to compare the performance of different deep learning architectures for
image classification and determine which model provides the best balance between accuracy and efficiency)

-----------------------------------------------------------------------------------------------------------------------------------

## Project Overview

This notebook walks through the complete machine learning pipeline:

* Loading and exploring the dataset
* Image preprocessing
* Building and training three different models
* Evaluating performance using multiple metrics
* Comparing the results
* Making predictions on test images

-----------------------------------------------------------------------------------------------------------------------------------

## Dataset

The project uses the **American Sign Language (ASL) Alphabet** dataset.

Each image represents a hand sign corresponding to a letter of the alphabet (A–Z, excluding letters that require motion).

### Data Preprocessing

* Normalize pixel values to the range **[0,1]**
* Reshape images for CNN input
* One-hot encode class labels
* Resize images for MobileNetV2

-----------------------------------------------------------------------------------------------------------------------------------

## Models Implemented

### 1. Convolutional Neural Network (CNN)

A custom CNN built using TensorFlow/Keras for image feature extraction and classification.

### 2. Multi-Layer Perceptron (MLP)

A fully connected neural network trained on flattened image vectors to provide a baseline comparison.

### 3. Transfer Learning (MobileNetV2)

A pretrained MobileNetV2 model with custom classification layers added on top for efficient feature extraction.

-----------------------------------------------------------------------------------------------------------------------------------

## Evaluation

The models are compared using:

* Accuracy
* Loss
* Precision
* Recall
* F1-Score

The notebook also includes prediction examples on test images to visualize model performance.

-----------------------------------------------------------------------------------------------------------------------------------

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Pandas
* Matplotlib
* scikit-learn
* Jupyter Notebook

-----------------------------------------------------------------------------------------------------------------------------------

## How to Run

1. Clone this repository.

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Install the required packages.

```bash
pip install tensorflow numpy pandas matplotlib scikit-learn
```

3. Open the notebook.

```bash
jupyter notebook project2.ipynb
```

4. Run all cells.

-----------------------------------------------------------------------------------------------------------------------------------

## Results

The notebook provides a side-by-side comparison of CNN, MLP, and MobileNetV2, allowing you to evaluate:

* Model accuracy
* Training performance
* Classification metrics
* Prediction quality

| Model | Accuracy |
|---|---|
| CNN | 100% |
| MLP | 62.27% |
| MobileNetV2 | 98.90% |

-----------------------------------------------------------------------------------------------------------------------------------

## Learning Objectives

This project demonstrates:

* Image preprocessing
* Deep learning with TensorFlow/Keras
* CNN architecture design
* Transfer learning
* Model evaluation and comparison
* Computer vision fundamentals

-----------------------------------------------------------------------------------------------------------------------------------


## Contributing

Contributions, suggestions, and improvements are welcome. Feel free to fork the repository and submit a pull request.

-----------------------------------------------------------------------------------------------------------------------------------

## License

This project is intended for educational purposes.
