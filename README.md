 
# Lossless Image Data Compression Using Neural Networks

## Authors
- P. Keerthi (L23ACS610)  
- SK. Reshma Bhanu (Y22ACS560)  
- M. Yaswanth Kumar (Y22ACS509)  
- G. Alakananda (Y22ACS450)  

---

## Implementation
[GitHub Repository] https://github.com/keerthi-pnathagani/Lossless-image-data-compression-using-Neural-Networks.git
---

## Overview
This project presents a Lossless Image Data Compression System using Neural Networks.  

The system uses a Convolutional Neural Network (CNN) to learn image patterns and reduce redundancy. Unlike traditional compression methods, this approach captures complex spatial relationships in images.

The system ensures:
- Exact reconstruction of the original image  
- No loss of pixel information  
- Secure storage using encryption  

---

## Key Features
- Lossless Image Compression  
- CNN-based Feature Extraction  
- Residual-Based Compression  
- Huffman Coding (Lossless Encoding)  
- AES Encryption for Security  
- Pixel-Level Accuracy Verification  
- Supports PNG, JPG, JPEG, BMP  

---

## System Architecture

The system follows a hybrid approach:

### 1. CNN Prediction
- Predicts pixel values using neural network  

### 2. Residual Calculation
- Difference between original and predicted image  

### 3. Huffman Encoding
- Compresses residual data efficiently  

### 4. AES Encryption
- Secures compressed data  

### 5. Reconstruction
- Rebuilds original image exactly  

---

## Tech Stack
- Python  
- PyTorch  
- NumPy  
- PIL (Python Imaging Library)  
- Matplotlib  
- PyCryptodome (AES Encryption)  

---

## Model Details
- **Model Type:** Convolutional Neural Network (CNN)  
- **Loss Function:** Mean Squared Error (MSE)  
- **Optimizer:** Adam  
- **Compression Type:** Lossless  

---
## How to Run
python train_model.py
python main.py

---
## Output
- Compressed Image Data  
- Encrypted Data  
- Reconstructed Image  
- Pixel Comparison Result (Lossless Verification)  
- Compression Ratio  

---

## Results
- Exact pixel reconstruction (Lossless)  
- Difference image = Completely Black (No error)  
- Compression Ratio ≈ 1.12×  
- Secure encrypted compressed data  

---

## Future Scope
- Integration with real-time systems
- Cloud-based compression
- GPU optimization
- Web-based interface
- Large-scale dataset support

