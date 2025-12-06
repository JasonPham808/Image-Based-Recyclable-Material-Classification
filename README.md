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

- **Artificial Neural Networks (ANN):** Up to 82% accuracy.
- **Convolutional Neural Networks (CNN):** Up to 80.9% accuracy.
- Results include accuracy, Cohen’s kappa, confusion matrices, and classification reports.
- CNNs best suited for real-world deployment and scalability.

## 🌟 Why Recruiters Should Care

- **Practical Impact:** Direct application to sustainability and AI-powered automation.
- **Technical Depth:** Experience in deep learning, image classification, and research-level evaluation.
- **Communication:** Clear presentation of data, models, and results in an interactive notebook.
- **Extensible:** Ready for transfer learning, larger datasets, and production deployment.

## 📂 Repo Structure

```
.
├── README.md
├── requirements.txt                # Dependencies for local/test runs
├── notebooks/
│   └── huy-hung_pham_mis780a2_task2.ipynb    # Main Colab notebook
├── src/
│   ├── data_loader.py              # For extensible data handling
│   ├── ann_model.py                # ANN architecture
│   ├── cnn_model.py                # CNN architecture
│   └── utils.py                    # Evaluation, visualization, helpers
```

## ▶️ Quick Start

1. **Run it on Colab:**  
   [Open Notebook Now](https://colab.research.google.com/gist/JasonPham808/ad2755628ef1986e7d63c972ec1df0d6/huy-hung_pham_mis780a2_task2.ipynb)

2. **Clone this repository:**  
   ```bash
   git clone https://github.com/JasonPham808/Image-Based-Recyclable-Material-Classification.git
   ```

3. **Install dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Add your data / Extend with new models:**  
   Use `/src/` scripts for modular development.

## 🎯 Next Steps (For Employers/Recruiters)

- Explore the notebook for a deep dive into technical details.
- Fork/adapt for your needs, or connect for collaboration!

## 📞 Contact

- **Author:** Jason Pham  
- [LinkedIn](https://www.linkedin.com/in/jasonpham808/)  
- Gmail: Jasonpham808@gmail.com  
- [GitHub](https://github.com/JasonPham808)

---

MIT License