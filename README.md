
<!-- Header Banner -->
<p align="center">
  <img src="Screenshot 2025-07-09 174724.png" alt="MNIST Unsupervised Learning" width="60%" />
</p>

<h1 align="center" style="color:#d63384;">MNIST Handwritten Digits — Unsupervised Learning with KMeans</h1>

<p align="center">
  <b>Explore clustering on digit images without using labels</b>  
  <br><br>
  <img src="https://img.shields.io/badge/Type-Unsupervised Learning-ff69b4?style=flat-square"/>
  <img src="https://img.shields.io/badge/Library-Scikit Learn-F7931E?style=flat-square"/>
  <img src="https://img.shields.io/badge/Dataset-MNIST-ffb6c1?style=flat-square"/>
</p>

---

## 📌 Project Overview

In this project, we apply **KMeans clustering** to the **MNIST handwritten digits** dataset without using any labels. Each image is a **28x28 grayscale grid**, flattened into a vector of **784 features**.

The goal: group similar digits together purely based on pixel intensity patterns, using unsupervised learning.

---

## 🧩 Step 1: Load and Visualize a Digit

We begin by reading the MNIST dataset and visualizing the very first image to understand the raw data format.

🖼️ **Output**: A grayscale image of the first handwritten digit in the dataset.

---

## 🔍 Step 2: Apply KMeans Clustering

Using **KMeans (n=10)**, the algorithm partitions the dataset into ten distinct clusters. Since the true labels are not provided, it identifies groups based on internal structure and visual similarity.

📌 **Insight**: Even without supervision, the model can group visually alike digits (like 1s, 7s, or 0s) by pixel distribution.

---

## 🔢 Step 3: Visualize Clusters

For a deeper look, we randomly sample and display **5 images from each cluster**. This helps us interpret what kind of digits are grouped together in each cluster, giving us a sense of the algorithm's understanding.

📷 **Output**: A 5-image preview for each cluster (0–9), showing handwritten digits grouped by pixel similarity.

---

## 🧠 Summary

This experiment highlights the power of **unsupervised learning** in image understanding:

- ✅ Applied KMeans clustering to high-dimensional image data
- ✅ No label supervision required
- ✅ Visualized groupings that reflect real-world digit similarity

---

## 📁 Dataset

- Source: [`mnist_data.csv`](#)
- Shape: 70,000 samples × 784 features
- Format: Each row represents a flattened grayscale digit image

---

## 📎 Tools Used

- Python (NumPy, Pandas, Matplotlib)
- Scikit-learn for clustering
- Matplotlib for visual output

---

## 💬 Final Note

Even without any knowledge of what the digits *are*, the model found structure just by analyzing pixel patterns. This is a foundational example of pattern discovery in computer vision using unsupervised methods.

---

<p align="center">
  <i>Thanks for reading — explore the clusters, and see what the model sees.</i>  
</p>
