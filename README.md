README FILE 
## Overview 
This project demonstrates how machine learning models can be attacked using adversarial techniques and how those attacks can be defended against. A convolutional neural network (CNN) was trained on the MNIST handwritten digit dataset, evaluated under normal conditions, attacked using the Fast Gradient Sign Method (FGSM), and then improved using adversarial training.

The goal of this project is to show how AI systems can perform very accurately under normal conditions but still be vulnerable to small, intentional input changes, and how those vulnerabilities can be reduced using defense methods. 

## Tools and Technologies 
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- MNIST Dataset

## Project Structure 
AI-Security-Final/ 
├── main.py (main project code) 
├── results/ (saved graphs) 
├── images/ (screenshots added) 
├── data/ (MNIST dataset auto-downloaded) 
├── paper/ (research paper) 
├── slides/ (presentation slides) 

## How to Run the Project 
1. Install dependencies: pip install torch torchvision matplotlib numpy
   
2. Run the program: py main.py
   
3. The script will:
  - Train a CNN model on MNIST
  - Evaluate baseline accuracy
  - Perform FGSM adversarial attacks
  - Apply adversarial training defense
  - Generate and save graphs in the results folder

## Model Summary 
A convolutional neural network was built to classify handwritten digits (0–9). The model uses convolution layers, activation functions (ReLU), and fully connected layers to learn patterns from image data. 

## Key Features Implemented 
  - CNN-based digit classification model
  - Baseline training on MNIST dataset
  - FGSM adversarial attack implementation
  - Multi-level epsilon testing (0.05, 0.15, 0.25)
  - Adversarial training defense method
  - Accuracy comparison visualization
  - Performance evaluation under normal and attack conditions

## Results Summary 
  - Baseline Model Accuracy: 98.23% - FGSM Attack Accuracy:
  - epsilon = 0.05 → 46.15%
  - epsilon = 0.15 → 38.71%
  - epsilon = 0.25 → 32.28%
  - Defended Model Accuracy (after adversarial training): 97.66%

These results show that the model performs very well under normal conditions but becomes significantly weaker when exposed to adversarial examples. After applying adversarial training, the model becomes much more resistant to attacks. 

## Key Concepts Demonstrated 
  - Machine Learning Model Training
  - Adversarial Machine Learning
  - Fast Gradient Sign Method (FGSM)
  - Model Vulnerability and Robustness
  - Adversarial Training Defense

## Graphs Generated The program automatically saves the following graphs in the results folder: 
  - FGSM attack accuracy vs epsilon values
  - Final comparison graph (baseline vs attack vs defended)

## Screenshots to Include in Report 
  - Baseline model accuracy output
  - FGSM attack results from terminal
  - Defended model accuracy output
  - Generated graphs from results folder

## What This Project Shows 
This project demonstrates that even highly accurate AI models can be easily fooled by small input changes. It also shows that retraining a model using adversarial examples can significantly improve its resistance to attacks. This is important in real-world AI systems such as cybersecurity, self-driving cars, and facial recognition systems. 

## Author Dante Williams 

## Course CTEC 450 – AI Security Project 

## Instructor Professor Carter 
