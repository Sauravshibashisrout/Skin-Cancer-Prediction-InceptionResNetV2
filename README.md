# Skin Cancer Prediction using InceptionResNetV2

A deep learning project for classifying skin cancer lesions using Transfer Learning with the **InceptionResNetV2** architecture, trained on the [HAM10000 (ISIC 2018 Task 3)](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000) dataset.

## Classes

The model classifies skin lesions into 7 categories:

| Code | Description |
|------|-------------|
| MEL | Melanoma |
| NV | Melanocytic Nevi |
| BCC | Basal Cell Carcinoma |
| AKIEC | Actinic Keratoses / Intraepithelial Carcinoma |
| BKL | Benign Keratosis-like Lesions |
| DF | Dermatofibroma |
| VASC | Vascular Lesions |

## Tech Stack

- Python
- TensorFlow / Keras
- InceptionResNetV2 (Transfer Learning)
- OpenCV, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

## Dataset

Download the ISIC 2018 Task 3 dataset and place the images in a folder named `ISIC2018_Task3_Training_Input/` before running the notebook.

## Usage

1. Clone the repo:
   ```bash
   git clone https://github.com/Sauravshibashisrout/Skin-Cancer-Prediction-InceptionResNetV2.git
   cd Skin-Cancer-Prediction-InceptionResNetV2
   ```

2. Install dependencies:
   ```bash
   pip install tensorflow opencv-python numpy pandas matplotlib seaborn scikit-learn
   ```

3. Open and run the notebook:
   ```bash
   jupyter notebook notebook.ipynb
   ```

## Model

Uses **InceptionResNetV2** pretrained on ImageNet as a feature extractor with custom classification layers fine-tuned for the 7-class skin lesion task.
