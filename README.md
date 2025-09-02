# 🐾 Cat vs Dog Classifier  

A deep learning project for classifying whether an image contains a **cat** or a **dog**, trained using convolutional neural networks (CNNs).  

This project uses PyTorch/TensorFlow (depending on your notebook) and provides both a training notebook and a saved model (`checkpoint.pth`) for inference.  

---

## 📂 Project Files
- **`CatOrDog.ipynb`** – Jupyter Notebook for training, validation, and testing the model.  
- **`checkpoint.pth`** – Saved trained model weights.  
- **`README.md`** – Documentation and usage instructions.  

---

## 📊 Dataset Requirements
- You can use **any dataset** of cats and dogs as long as it follows this guideline:  
  - **Balanced dataset** (similar number of cat and dog images).  
  - **At least 500 images per class** (e.g., 500 cats + 500 dogs minimum).  
  - Images should be organized in folders:
    ```
    dataset/
    ├── train/
    │   ├── cats/
    │   └── dogs/
    ├── val/
    │   ├── cats/
    │   └── dogs/
    └── test/
        ├── cats/
        └── dogs/
    ```

---

## ⚙️ Installation & Setup
1. Clone or download this repository.  
2. Install required dependencies:  
   ```bash
   pip install torch torchvision matplotlib numpy
