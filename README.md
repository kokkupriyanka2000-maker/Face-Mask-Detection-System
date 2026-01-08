# Face Mask Detection System

This project implements a Face Mask Detection system using Deep Learning.
The system classifies whether a person is wearing a face mask or not from an image.

The entire project is developed and trained using Google Colab.

---

## Project Description

Face Mask Detection is a binary image classification problem.
A Convolutional Neural Network (CNN) is trained on images of faces with masks
and without masks to automatically identify mask usage.

---

## Dataset

The dataset consists of two classes:
- Mask
- No Mask

Images are resized and normalized before training.

---

## Model Architecture

- Convolutional Neural Network (CNN)
- Activation Function: ReLU
- Output Layer: Sigmoid
- Loss Function: Binary Crossentropy
- Optimizer: Adam

---

## Trained Model

The trained model file (`face_mask_detector.h5`) exceeds GitHub’s file size limit.

Download the model from Google Drive using the link below:

Model Link:  
https://drive.google.com/file/d/1lldNdiyivHCqHtzSU4HY1mez3vv0ljAq/view?usp=drivesdk

---

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Google Colab

---

## How to Run the Project

1. Open the notebook in Google Colab
2. Upload the dataset (if training again)
3. Download and upload `face_mask_detector.h5` into Colab
4. Upload a test image
5. Run all cells to get prediction results

---

## Testing

The model is tested using new images uploaded manually in Google Colab.
The output is displayed as either:

- Mask
- No Mask

---

## Results

The model successfully classifies face images with and without masks
with good accuracy.

---

## Author

Kokku Priyanka

