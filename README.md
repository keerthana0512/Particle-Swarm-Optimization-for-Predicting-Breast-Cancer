# Breast Cancer Detection using Machine Learning

This project aims to detect breast cancer using machine learning algorithms applied to medical images. The system utilizes convolutional neural networks (CNN) for feature extraction, particle swarm optimization (PSO) for feature selection, and support vector machine (SVM) for classification.

## System Requirements Specifications

### Hardware Requirements
- **Machine Name:** HP
- **Processor:** Intel Core i5, 2.50 GHz
- **RAM:** 8 GB

### Software Requirements
- **Operating System:** Windows 10
- **Front End Tools:** Python, Data Analytics
- **Web Browser:** Google Chrome
- **Software:** Jupyter Notebook

## Implementation

### Working Principle
1. **Feature Extraction (CNN - ResNet):** Extracts features from breast histopathology images.
2. **Feature Selection (PSO):** Utilizes Particle Swarm Optimization to select relevant features.
3. **Classification (SVM):** Predicts the accuracy of breast cancer detection using Support Vector Machine.

## Dataset Used
The dataset comprises 2,77,524 50x50 pixel RGB digital image patches derived from 162 H&E-stained breast histopathology samples. These images represent small patches extracted from digital images of breast tissue samples. 

- **Classes:**
  - **Malignant (1):** Ductal Carcinoma, Lobular Carcinoma, Mucinous Carcinoma, Papillary Carcinoma
  - **Benign (0):** Adenosis, Fibroadenoma, Phyllodestumor, Tubular-adenoma

## Published Paper
A paper based on this project has been published in IEEE Xplore. You can access it.(https://ieeexplore.ieee.org/document/10060690).

## Usage
To utilize this project, follow these steps:
1. Clone the repository to your local machine.
2. Ensure you have the required hardware and software specifications.
3. Install necessary dependencies.
4. Run the Jupyter Notebook file.
5. Follow the instructions within the notebook for data preprocessing, feature extraction, feature selection, and classification.

