# Image-Based Recyclable Material Classification

**Automated classification of recyclable materials using deep learning (ANN, CNN), optimized for Colab.**

---

## 🚀 Project Overview

This project applies state-of-the-art deep learning to the real-world challenge of **recyclable material classification**. By automating sorting, we boost recycling efficiency—directly supporting environmental sustainability and operational productivity.

- **Core Notebook:**  
  [huy-hung_pham_mis780a2_task2.ipynb - Colab Link](https://colab.research.google.com/gist/JasonPham808/ad2755628ef1986e7d63c972ec1df0d6/huy-hung_pham_mis780a2_task2.ipynb)
    - Data loading, model construction, training, and evaluation in one place!
    - Try it instantly in Google Colab, no setup required.

## 🧑‍💻 Tech Stack

- **Python 3**
- **TensorFlow / Keras** (ANNs & CNNs)
- **scikit-learn, pandas, numpy**
- **Google Colab** (cloud-based, zero install!)
- **Jupyter/Colab Notebooks**

## 📷 Dataset

- **2,691 labeled images**
- Six categories: Cardboard, Clothing, Paper, Metal, Green Glass, and White Glass.
- Balanced train/test split for robust evaluation.

## 📊 Results
**Comparative Analysis: ANN vs. CNN**
  - ANN Model 3: 
    - Highest accuracy: 82.1%
    - Cohen’s kappa: 0.786
    - Test loss: 0.812
    - Architecture: 2 hidden layers, dropout rate 0.5, RMSprop optimization
  - CNN Model 6:
    - Accuracy: 80.9%
  **Key Insights:**
    - ANN limitations: Cannot effectively exploit spatial hierarchies of image data.
    - CNN advantages: Better differentiation of visually similar categories; captures edges and textures well.
    - CNNs scale efficiently with larger datasets; more robust to environmental variations.
  
**Worst Performing Class:**
  - Misclassification is prevalent in clothing items and glass variants (green and white).
**Clothing Misclassifications:**
    - High intra-class variability (different fabrics, colors, textures).
    - Often confused with cardboard due to color similarities.
**Glass Misclassifications:**
    - Similar visual characteristics (transparency, reflective surfaces).
    - - Difficulty in differentiation even with advanced CNNs.
  
**Challenges Identified:**
- Class imbalance and visual similarity.
- Potential solutions: 
- Collect more diverse training samples.
- Apply data augmentation techniques.
- Use more advanced architectures to focus on subtle differences.

## Potential Approaches for Improvement and Sustainable Impact
 **Data Collection**
  - Increase dataset size to mitigate overfitting and enhance generalization.
  - Balance classes by expanding underrepresented categories (e.g., clothing, green glass, white glass) with diverse samples.

**Data Processing**
  - Implement image augmentation (rotations, flips, brightness adjustments, Gaussian noise) to simulate variability and reduce overfitting.
  - Use background removal, color normalization, and edge detection to focus on materials.
  - Apply noise reduction filters to minimize reflections and lighting artifacts.

**Data Formatting**
  - Standardize image size (e.g., 128×128 or 224×224 pixels) for streamlined training.
  - Experiment with alternative color spaces (grayscale, HSV) for better material distinction.
  - Enhance annotations with metadata (lighting conditions, source environment) for future multi-modal model development.

**Modeling Architecture**
  - Explore deeper architectures with additional convolutional layers, residual connections, or attention mechanisms.
  - Utilize ensemble methods by combining CNNs or hybrid approaches to improve robustness.


## How to access this project

1. **Run it on Colab:**  
   [Open Notebook Now](https://colab.research.google.com/gist/JasonPham808/ad2755628ef1986e7d63c972ec1df0d6/huy-hung_pham_mis780a2_task2.ipynb)

2. **Clone this repository:**  
   ```bash
   git clone https://github.com/JasonPham808/Image-Based-Recyclable-Material-Classification.git
   ```

## 📞 Contact

- **Author:** Jason Pham  
- [LinkedIn](https://www.linkedin.com/in/jasonpham808/)  
- Gmail: Jasonpham808@gmail.com  
- [GitHub](https://github.com/JasonPham808)
