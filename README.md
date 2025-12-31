# Cats-and-dogs-Classifier

This project is a part of the **freeCodeCamp Machine Learning with Python certification**.  
The goal is to build a Convolutional Neural Network (CNN) that can classify images as **cat** or **dog**.

I worked on this project using **Google Colab**, following the structure and instructions provided by freeCodeCamp, and filled in the required parts step by step.

---

## Project Overview

- Built a CNN using **TensorFlow 2.x and Keras**
- Used image data generators to load and preprocess images
- Applied **data augmentation** to reduce overfitting
- Trained the model on labeled cat and dog images
- Evaluated the model on unseen test images
- Achieved the minimum required accuracy to pass the challenge

This project helped me understand how image classification works in practice using deep learning.

---

## What I Learned

- How to use `ImageDataGenerator` for loading and preprocessing images
- Why data augmentation is important when the dataset is small
- How convolution and pooling layers work together
- How to track training vs validation accuracy and loss
- How to make predictions on unseen images

---

## Dataset Structure

The dataset is automatically downloaded in the notebook and has the following structure:
cats_and_dogs/
├── train/
│ ├── cats/
│ └── dogs/
├── validation/
│ ├── cats/
│ └── dogs/
└── test/
├── 1.jpg
├── 2.jpg
└── ...


- Training set: labeled images of cats and dogs  
- Validation set: used to evaluate during training  
- Test set: unlabeled images used for final predictions  

---

## Model Architecture (High Level)

- Convolutional layers with ReLU activation
- MaxPooling layers to reduce spatial dimensions
- Flatten layer
- Fully connected (Dense) layer
- Output layer with sigmoid activation (binary classification)

The model is compiled using:
- **Optimizer:** Adam  
- **Loss function:** Binary Crossentropy  
- **Metric:** Accuracy  

---

## How to Run This Project

This project was developed and tested using **Google Colab**.

### Steps:
1. Open the notebook in Google Colab.
2. Run the cells in order from top to bottom.
3. The dataset will be downloaded automatically.
4. The model will train and display accuracy/loss graphs.
5. Final predictions will be shown for the test images.

No additional setup is required when using Google Colab.

---

## Results

- The model meets the **freeCodeCamp requirement of at least 63% accuracy**
- Training and validation performance is visualized using plots
- Predictions are shown as confidence percentages for cats and dogs

---

## Notes

- This project focuses on understanding the **end-to-end CNN workflow**
- The goal was learning and experimentation, not building a production-grade model
- Accuracy can be improved further with more tuning and training time

---

## Acknowledgement

This project is part of the **freeCodeCamp Machine Learning with Python Certification**  
and was completed using the provided starter notebook and dataset.
