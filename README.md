# Morphological Classification of Cyanobacteria Using MobileNet and MobileNetV2

This repository presents two deep learning models to classify toxigenic cyanobacteria from RGB microscopic images based on their morphology:

- **MobileNet** model implemented in `mobilenet.ipynb`
- **MobileNetV2** model implemented in `mobilenetV2.ipynb`

Both models utilize transfer learning and are trained on RGB images of cyanobacteria to classify genera for water quality monitoring purposes.

> ✅ Developed as part of the **Summer Semester Research Project** at **IIIT Naya Raipur**

---

## 📌 Objective

- Classify cyanobacterial genera using RGB image morphology
- Compare MobileNet vs MobileNetV2 in terms of accuracy, efficiency, and generalization
- Deploy a lightweight, real-time-capable model for microscopy image analysis

---

## 📁 Files in This Repository

| File Name            | Description                                                              |
|----------------------|--------------------------------------------------------------------------|
| `mobilenet.ipynb`    | MobileNet model trained on cyanobacteria RGB images                      |
| `mobilenetV2.ipynb`  | Independent MobileNetV2 model for the same task                          |
| `results/`           | Output visualizations (accuracy/loss curves, predictions, etc.)          |
| `README.md`          | Project overview and usage guide                                         |

---

## 🧠 Model Comparison

| Metric               | MobileNet (`mobilenet_rgb.ipynb`) | MobileNetV2 (`Summer.ipynb`)  |
|----------------------|-----------------------------------|-------------------------------|
| Accuracy             | 98.12%                            | 97.68%                        |
| Training Loss        | 0.073                             | 0.062                         |
| Epochs               | 40                                | 40                            |
| Batch Size           | 32                                | 32                            |
| Optimizer            | Adam                              | Adam                          |
| Pretrained Base      | MobileNet (ImageNet)              | MobileNetV2 (ImageNet)        |
| Input Format         | Microscopy Images                 | Microscopy Images             |

---


---

## 📦 Dataset

Microscopic RGB images of toxigenic cyanobacteria genera were used. Due to data sharing restrictions, the original dataset is not public.

However, a similar dataset can be used for experimentation:

- 🔗 **[Algae Classification Dataset – Kaggle](https://www.kaggle.com/datasets/andrewmvd/algae-classification)**

This open dataset includes microscopic algae images suitable for morphological classification tasks.

---

## 📥 Installation

Install all required dependencies using pip:

pip install -r requirements.txt
