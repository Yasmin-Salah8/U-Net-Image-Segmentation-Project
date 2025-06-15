# U-Net-Image-Segmentation-Project
This repository contains a Jupyter Notebook implementing an image segmentation pipeline using a U-Net deep learning model. It includes data preprocessing, augmentation, normalization, model training, and evaluation.

## 📂 Project Structure

- **Resizing**: Input images are resized for consistency.
- **Image Augmentation**: Enhances the dataset using various transformations.
- **Train-Test Split**: Dataset is divided for training and evaluation.
- **Normalization**: Pixel values are scaled to improve model performance.
- **Model Architecture**: A U-Net model is built for segmentation tasks.
- **Training**: The model is trained using suitable loss functions and optimizers.
- **Evaluation**: Model performance is assessed using accuracy and visualization of results.

## 🛠 Technologies Used

- Python 3
- NumPy, Pandas
- TensorFlow / Keras
- OpenCV / PIL
- Jupyter Notebook

## 🧠 Model

The core of this project is the **U-Net architecture**, which is widely used for biomedical and satellite image segmentation due to its encoder-decoder structure with skip connections.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/unet-image-segmentation.git
   cd unet-image-segmentation
