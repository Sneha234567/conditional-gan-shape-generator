# Conditional GAN Shape Generator

## 📌 Overview
This project implements a **Conditional Generative Adversarial Network (CGAN)** to generate simple geometric shapes (Circle, Square, Triangle) based on textual labels or category inputs.  
It is part of the internship assignment to demonstrate the use of conditional inputs in GANs for image generation.

---

## 🎯 Features
- Conditional GAN architecture
- Generates shapes according to given labels
- Saves generated images automatically
- Supports GPU acceleration (if available)
- Simple, easy-to-understand code structure

---

## 🗂 Project Structure
├── train_shapes.py # Model training script
├── generate_shapes.py # Script to generate images using the trained model
├── generator_shapes.pth # Saved trained model weights
├── requirements.txt # Python dependencies
├── cgan_samples/ # Images generated during training
├── generated_shapes/ # Images generated from saved model
└── README.md # Project documentation

---

## ⚙️ Requirements
Before running the project, install the dependencies:
```bash
pip install -r requirements.txt
🚀 How to Run
1️⃣ Train the Model
python train_shapes.py
This will train the CGAN and save the model as generator_shapes.pth
Training progress images will be saved in the cgan_samples/ folder.
2️⃣ Generate Shapes
python generate_shapes.py
Uses the saved model to generate new shapes.
Output images will be saved in the generated_shapes/ folder.

📊 Dataset
A synthetic dataset is created programmatically:
Classes: Circle, Square, Triangle
Image Size: 64x64 pixels
Color: White shapes on a black background
200 images per class

📈 Performance Metrics
Since this is a generative model, traditional accuracy is not directly applicable.
Instead, qualitative visual inspection is used to validate:
Correctness of generated shapes
Consistency between generated shapes and given labels

📂 Output Samples
Training Samples (cgan_samples/):
Generated after each epoch to monitor progress.
Final Generated Shapes (generated_shapes/):
Produced using the trained model.

🛠 Technologies Used
Python 3
PyTorch – Deep learning framework
Torchvision – Image transformations and utilities
PIL (Pillow) – Image generation and manipulation
TQDM – Training progress visualization
## Tasks

- **Task 1**: Conditional GAN Shape Generator → [`Task1_Conditional_GAN`](./Task1_Conditional_GAN)
- **Task 2**: Nullclass Dataset Project → [`Task2_Nullclass_Dataset_Project`](./Task2_Nullclass_Dataset_Project)


📌 Author
Sneha Prasad
