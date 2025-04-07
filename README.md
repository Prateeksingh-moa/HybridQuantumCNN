# 🧬 Hybrid Quantum-Classical CNN for Skin Cancer Detection

A cutting-edge experiment in combining **Quantum Computing** with **Deep Learning** to classify skin lesions from dermatoscopic images. This project introduces a **Hybrid Quantum Convolutional Neural Network (Hybrid QCNN)**, demonstrating how quantum circuits can be integrated into classical models to push the boundaries of medical image analysis.

---

## 🌟 Project Highlights

- ⚛️ **Quantum-Enhanced Learning**: Utilizes a quantum variational circuit embedded into a classical CNN using **Pennylane**, enabling the model to learn complex, high-dimensional patterns.
- 🧠 **Skin Lesion Classification**: Targets multi-class classification of 7 different skin diseases using the **HAM10000** dataset.
- 🔬 **Medical Application**: Aimed at assisting early diagnosis of melanoma and other skin conditions through advanced modeling techniques.

---

## 📁 What's Inside

| File | Description |
|------|-------------|
| `hybrid-quantum-cnn.ipynb` | Jupyter Notebook containing the full implementation — data preprocessing, hybrid model architecture, training, and evaluation. |

---

## 🧠 Model Architecture

> A fusion of classical deep learning and quantum computing.

- **Classical CNN Layers**: Convolutions and pooling to extract hierarchical visual features.
- **Quantum Layer**: A variational quantum circuit (VQC) with entanglement and trainable parameters, implemented via Pennylane and inserted as a custom Keras layer.
- **Fully Connected Layers**: Final dense layers for classification across 7 skin lesion categories.

---

## 🧪 Dataset: HAM10000

- **Source**: Human Against Machine with 10,000 images
- **Classes**: Melanoma, Melanocytic Nevi, Basal Cell Carcinoma, Actinic Keratoses, and others
- **Preprocessing**: Resized images, normalized pixel values, one-hot encoded labels

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/your-username/hybrid-quantum-cnn.git

# Install required libraries
pip install -r requirements.txt

# Launch the notebook
jupyter notebook hybrid-quantum-cnn.ipynb
