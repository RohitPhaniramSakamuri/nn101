# Number Recognition with MNIST (Using NumPy & Math)

## Getting Started (On Windows)

### Prerequisites
Ensure you have Python installed on your system.

### Setting Up Your Virtual Environment
Using PowerShell, follow these steps to set up and manage your virtual environment:

1. **Allow Virtual Environment Usage in PowerShell:**
   ```powershell
   Set-ExecutionPolicy -Scope Process -ExecutionPolicy Unrestricted
   ```
2. **Create a Virtual Environment (Named `env`):**
   ```powershell
   python -m venv env
   ```
3. **Activate the Virtual Environment:**
   ```powershell
   env/Scripts/Activate.ps1
   ```
4. **Update Python Modules (After Starting a New Session or Pulling Changes):**
   ```powershell
   pip install -r requirements.txt
   ```
5. **Freeze Dependencies Before Pushing to the Repository:**
   ```powershell
   pip freeze > requirements.txt
   ```

## Procedure
This project focuses on **Number Recognition** using the **MNIST dataset**, but without relying on PyTorch or any deep learning framework. Instead, it leverages **NumPy** and **Math** to build an intuitive understanding of image classification. 

The neural network should be able to classify images of handwritten digits to the actual number.

# The Math
* The images from the MNIST dataset are 28px x 28px = 784px, each pixel is a value ranging from 0-255 (grayscale: 0 is black, 255 is white).
* Let there me "m" such training images. Then, there is an matrix 'X' of images, dimensions as m x 784 i.e, m rows and 784 columns, in each column would be a value of range [0, 255].
* We transpose X (I don't know why yet, I intend to find out), such that there are now 784 rows and m columns.

# The Model Architecture
* Layer 0: Input Layer - 784 nodes, for each pixel.
* Layer 1: Hidden Layer - 10 nodes, connected to (all?) nodes from Layer 0.
* Layer 2: Output Layer - 10 nodes, each node corresponds to a whole number ∈ [0, 9]
   ![image](https://github.com/user-attachments/assets/e624fc16-d1b6-407a-bbea-7813a30f4641)


# Training/More Math?
* There are 3 parts to training this model:


## 📂 Project Structure
```
├── venv/                # Virtual environment (ignored in .gitignore)
├── src/                 # Source code for number recognition
│   ├── 
├── requirements.txt     # Dependencies
├── README.md            # This file
```

---
**Note:** This is a learning-focused project aimed at building an intuition for image classification from the ground up.
