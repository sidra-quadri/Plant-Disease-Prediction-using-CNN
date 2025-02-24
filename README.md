# Plant Prediction Using CNN

## Project Overview

This project is a **Plant Disease Prediction** system developed using **Artificial Intelligence (AI)** and **Machine Learning (ML)** techniques. The application uses a **Convolutional Neural Network (CNN)** to classify plant leaf images and predict whether the plant has a disease. The goal of the project is to help farmers and gardeners quickly identify plant diseases from leaf images, which can help in timely intervention and crop protection.

## Key Technologies Used

- **Gradio**: A user-friendly library for building interactive web applications. I used Gradio to create a simple interface where users can upload leaf images and get disease predictions.
  
- **Convolutional Neural Network (CNN)**: A deep learning model used for image classification. CNNs are ideal for this task, as they can effectively process and classify visual data.

## Features

- **Leaf Image Input**: Users can upload a leaf image to the system.
- **Disease Prediction**: The model will analyze the image and predict the disease the plant might have (e.g., Apple Black Rot).
- **Interactive UI**: The Gradio-based interface allows users to upload images and get predictions in a matter of seconds.

## Installation

### Prerequisites

Before you start, ensure you have the following installed:
- Python 3.x
- Gradio
- Required libraries (`tensorflow`, `keras`, `numpy`, etc.)

### Step-by-step Instructions

1. **Clone the Repository**:
    ```bash
    git clone <repository-url>
    cd <project-directory>
    ```

2. **Run**:
    ```bash
    plant.ipynb
    ```
    This will run the project, and you can access the application via your browser on Google colab or Jupyter.

3. **Start Predicting**:
    - Open the provided link in your browser.
    - Upload a leaf image of a plant.
    - Click on the "Predict" button to see the disease prediction.

## How It Works

1. **Leaf Image Input**: The user uploads an image of a plant leaf showing possible signs of disease.
2. **Preprocessing**: The image is preprocessed to match the model’s input format (resize, normalization, etc.).
3. **Prediction**: The CNN model classifies the image and predicts the plant disease.
4. **Output**: The disease prediction, such as "Apple Black Rot," is displayed for the user.

## Example

Here is an example of how you can use the system:

- **Input**: A leaf image of a plant showing symptoms of a disease.
- **Output**: The system predicts the disease as "Apple Black Rot."

## Glimpse of the project


![alt text](https://github.com/sidra-quadri/Plant-Disease-Prediction-using-CNN/blob/7fdb1a16b6b83a606da11f36494b5d541e8fdadb/Re_img1.png)
<br><br>

![alt text](https://github.com/sidra-quadri/Plant-Disease-Prediction-using-CNN/blob/7fdb1a16b6b83a606da11f36494b5d541e8fdadb/Re_img2.png)
<br><br>

![alt text](https://github.com/sidra-quadri/Plant-Disease-Prediction-using-CNN/blob/7fdb1a16b6b83a606da11f36494b5d541e8fdadb/Re_img3.png)
