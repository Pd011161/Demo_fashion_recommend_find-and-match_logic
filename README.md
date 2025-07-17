# 🧥 Fashion Finding and Matching

A Jupyter Notebook for image-based fashion product searching and outfit style matching using FashionCLIP embeddings.
[link](https://colab.research.google.com/drive/1QbWKW1QuVNCwPW-H08oT6YuKV32R-1X8?usp=sharing)

---

## 📖 Project Overview

This project allows users to search for and match fashion products (such as shirts, pants, or other items) based on images and product descriptions.  
By leveraging deep learning (FashionCLIP), the system compares the visual and textual features of fashion items for recommendation and matching purposes.

---

## 🚀 Features

- **Fashion item searching:** Find products by image or text.
- **Outfit/style matching:** Suggest fashion items that go well together.
- **Supports Thai and English descriptions**
- **Simple and interactive via Jupyter Notebook**

---

## 🛠️ Tech Stack

- Python 3.x
- Jupyter Notebook
- [FashionCLIP (Huggingface)](https://huggingface.co/salesforce/FashionCLIP)
- Pandas, NumPy
- Pillow (PIL), Requests, tqdm

---

## ⚡️ Getting Started

**1. Install dependencies**

```bash
pip install pandas numpy pillow requests tqdm
pip install fashion-clip
```

**2. Open the notebook**

Open fashion_finding_and_matching.ipynb in Jupyter Notebook, JupyterLab, or VSCode.

**3. Prepare your data**

Ensure you have a .csv file containing at least the image URLs and product descriptions.

Update the notebook's file paths as needed.

**4. Follow the notebook steps**

The notebook demonstrates how to encode images and text, calculate similarity, and perform matching.


---

## 🖼️ Example Usage
Provide image URLs and English/Thai product descriptions.

The notebook will generate embeddings using FashionCLIP.

Match items by similarity (e.g., find a shirt that matches uploaded pants).

---

## ⚠️ Notes
If you encounter issues with Thai text, try changing the CSV encoding to 'utf-8-sig' or 'cp874'.

Internet connection is required for downloading images from URLs.

You can modify the notebook to use local image files if needed.

---

## 📝 Quick Summary
Fashion Finding and Matching enables anyone to use AI for smart outfit recommendations using images and product descriptions—all in an interactive notebook.