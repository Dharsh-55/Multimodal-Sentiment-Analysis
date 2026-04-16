# 🧠 Multimodal Sentiment Analysis using CNN + BiLSTM

## 📌 Overview

This project implements a **multimodal deep learning system** that combines **image data** and **text data** to perform classification. The model integrates a **CNN (MobileNetV2)** for image feature extraction and a **BiLSTM** for text understanding, followed by a **fusion layer** for final prediction.

The system is designed to demonstrate how combining multiple data modalities improves classification performance compared to single-modality approaches.

---

## 🎯 Objectives

* Build a multimodal deep learning pipeline
* Extract features from both images and text
* Fuse representations for improved prediction accuracy
* Compare performance across image-only, text-only, and multimodal models

---

## 🧠 Model Architecture

### 🔹 Image Branch

* **MobileNetV2 (CNN)**
* Extracts visual features from input images

### 🔹 Text Branch

* Tokenization + Vocabulary building
* **BiLSTM (Bidirectional LSTM)** for sequence modeling

### 🔹 Fusion Layer

* Concatenates image and text features
* Fully connected layers for classification

---

## ⚙️ Workflow

1. Install and import required libraries
2. Generate dataset (images + CSV metadata)
3. Visualize class distribution and sample data
4. Build vocabulary from text reviews
5. Train/Validation/Test split with PyTorch Dataset
6. Model building (CNN + BiLSTM + Fusion)
7. Model training (15 epochs)
8. Plot training loss and accuracy curves
9. Evaluate model on test data
10. Generate classification report
11. Plot confusion matrix heatmap
12. Perform ablation study (Text vs Image vs Multimodal)
13. Run live predictions on new samples
14. Summarize results in final comparison table

---

## 📊 Key Features

* Multimodal learning (Image + Text)
* Transfer learning using MobileNetV2
* Sequence modeling using BiLSTM
* Fusion-based classification
* Ablation study for performance comparison
* Visualization of results (graphs & heatmaps)

---

## 🏗️ Tech Stack

* **Language:** Python
* **Frameworks:** PyTorch, Torchvision
* **Libraries:**

  * NumPy, Pandas
  * Matplotlib, Seaborn
  * Scikit-learn

---

## 📂 Project Structure

```bash
├── data/                  # Images and CSV dataset
├── preprocessing/        # Data cleaning & tokenization
├── models/               # CNN, BiLSTM, Fusion model
├── notebooks/            # Training & experiments
├── results/              # Plots, confusion matrix, reports
├── README.md
```



---

## ▶️ Usage

1. Prepare dataset (images + text CSV)
2. Run training pipeline
3. Evaluate model performance
4. Test with new inputs for live predictions

---

## 📈 Results

* Multimodal model outperforms individual modalities
* Image-only model captures visual patterns
* Text-only model captures semantic meaning
* Fusion model provides the best overall accuracy

---

## 🔬 Ablation Study

| Model Type | Performance |
| ---------- | ----------- |
| Text Only  | Moderate    |
| Image Only | Moderate    |
| Multimodal | Highest     |

---




