# 🐶 Cats vs Dogs Image Classification

A Convolutional Neural Network (CNN) built using **TensorFlow** and **Keras** to classify images of **cats vs dogs**. The model is trained using the [Kaggle Dogs vs Cats dataset](https://www.kaggle.com/datasets/salader/dogs-vs-cats), with GPU acceleration via Google Colab.

## 🚀 Features

- Download and unzip Kaggle dataset via Kaggle API
- Real-time training in Google Colab (GPU-enabled)
- Custom CNN architecture for image classification
- Image preprocessing, augmentation, and normalization
- Training/validation accuracy and loss visualization
- Model saving for inference/deployment

## 📁 Dataset

- Source: [Kaggle - salader/dogs-vs-cats](https://www.kaggle.com/datasets/salader/dogs-vs-cats)
- Format: ~25,000 labeled images (cats and dogs) in `.jpg` format
- Size: ~1.06 GB

## 🧠 Model Architecture

- Input: 128x128 RGB images
- Several Conv2D + MaxPooling2D layers
- Dropout to prevent overfitting
- Flatten + Dense layers
- Output: Binary classification (sigmoid)

## 🛠️ Setup & Usage

### 1. Clone Repository and Upload to Colab (or run locally)

> Step-by-step instructions are inside the Jupyter Notebook.

### 2. Upload `kaggle.json` to `/content/`

Obtain your Kaggle API key from [Kaggle Account → API](https://www.kaggle.com/account) and upload the `kaggle.json` file to the root of your Colab environment.

### 3. Run the Notebook

The notebook handles:
- API configuration
- Dataset download/unzip
- Model training
- Evaluation & export

## 🖼️ Sample Output

- `Accuracy: ~80% on validation`
- Confusion matrix (optional)
- Plots for loss, accuracy vs. epochs

## 📌 Requirements

> Automatically installed in Google Colab

- Python ≥ 3.6
- TensorFlow/Keras ≥ 2.8
- NumPy, Matplotlib, Kaggle API


**Happy Learning 🧠 with TensorFlow!**  
For improvements or bug reports, feel free to open an issue or submit a PR.

--- 
