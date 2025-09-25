# Classifying Traffic Signs with a Simple CNN

This project demonstrates how to classify traffic signs using a **Convolutional Neural Network (CNN)** implemented in MATLAB.  
The entire workflow — data loading, preprocessing, model building, training, and evaluation — is contained in the provided `.mlx` live script.

---

## Motivation

Traffic sign recognition is an important component of autonomous driving and driver-assistance systems.  
This project shows how even a simple CNN, built and trained from scratch, can achieve strong performance on this task.

---

## Dataset

You’ll need a labeled dataset of traffic signs to run the script. Common choices:

- **German Traffic Sign Recognition Benchmark (GTSRB)**  
- Any custom dataset with traffic sign images organized into classes

Make sure the dataset path in the script points to your data.

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/dreambigbibek/Classifying-Traffic-Signs-with-a-Simple-CNN.git
   cd Classifying-Traffic-Signs-with-a-Simple-CNN
2. Open MATLAB.

3. Launch the live script:

open('traffic_sign_classification.mlx')


4. Run all sections (Run All in the Live Editor toolbar) or step through the script interactively.

   ##Model Architecture

The CNN defined in the script typically follows:

Convolution → ReLU → Max Pooling

Additional convolution/pooling layers

Fully connected layers → Softmax output

Loss: Cross-Entropy
Optimizer: Adam (default in Deep Learning Toolbox)

