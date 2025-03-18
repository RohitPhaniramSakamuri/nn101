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
