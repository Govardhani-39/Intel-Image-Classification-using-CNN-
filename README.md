# Intel-Image-Classification-using-CNN-
This project implements a Convolutional Neural Network (CNN) to classify images from the Intel Image Classification dataset. The model is built using PyTorch and trained to distinguish between 6 types of natural scenes.
## 📂 Dataset

The dataset includes images classified into the following categories:

- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

📌 You can download the dataset from [Intel Image Classification Dataset on Kaggle](https://www.kaggle.com/datasets/puneet6060/intel-image-classification).

## 🧠 Model Architecture

- Framework: PyTorch
- Layers: Conv2D, MaxPooling, ReLU, Fully Connected
- Loss: CrossEntropyLoss
- Optimizer: Adam

## 🏋️ Training

- Batch Size: 32
- Epochs: 10 (customize as needed)
- Learning Rate: 0.001


## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/intel-image-classification.git
   cd intel-image-classification
2.Install dependencies:
pip install -r requirements.txt
3.Run the notebook:
jupyter notebook intel_problem_statement2.ipynb
