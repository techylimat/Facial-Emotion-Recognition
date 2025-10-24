# Facial Emotion Recognition with CNN 

This project implements a **Facial Emotion Recognition (FER)** system using **Convolutional Neural Networks (CNNs)** in **PyTorch**.  
The model is trained to classify human facial expressions into seven emotion categories.

---

## Project Overview

Facial Emotion Recognition (FER) is an essential application in affective computing and human–computer interaction.  
This project leverages a CNN architecture trained on a facial expression dataset to detect emotions such as:

- 😡 Angry  
- 🤢 Disgust  
- 😱 Fear  
- 😄 Happy  
- 😐 Neutral  
- 😢 Sad  
- 😲 Surprise  

The model achieves around **59% overall accuracy** on the test dataset, showing promising results for a basic CNN model.

---

## Model Architecture

The CNN model consists of:

- 3 convolutional layers with ReLU activation  
- Max-pooling layers for downsampling  
- Dropout layers for regularization  
- Fully connected layers for classification  
- Softmax output layer for predicting emotion probabilities  

---

## Tech Stack

- **Language:** Python  
- **Framework:** PyTorch  
- **Visualization:** Matplotlib, Seaborn  
- **Libraries:** NumPy, scikit-learn, tqdm  

---

## Dataset

You can use the **FER2013** dataset or any custom facial expression dataset with 7 emotion classes.  
Each image should be **48x48 grayscale** and labeled accordingly.

## How to Run

 **Clone this repository**
   ```bash
   git clone https://github.com/techylimat/facial-emotion-recognition.git
   cd facial-emotion-recognition
