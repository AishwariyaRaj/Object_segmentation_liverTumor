# 🧠 Liver Tumor Segmentation 

## 📝 Overview

This project performs semantic segmentation of liver tumors using a U-Net-based convolutional neural network on 3D medical scans from the LiTS (Liver Tumor Segmentation) dataset. It is designed for efficient training on 2D slices and tested in a resource-constrained environment

---

## 🧰 Features

✅ Preprocessing of .nii files into 2D slices

✅ Filtering out empty background slices to reduce noise

✅ U-Net architecture for medical image segmentation

✅ Evaluation and prediction visualization

✅ Designed for use in Google Colab with limited storage

---
Clone the repo & upload dataset :
```
git clone https://github.com/AishwariyaRaj/Object_segmentation_liverTumor.git

```
Install dependencies with:
```
!pip install nibabel opencv-python matplotlib tensorflow

```

## 📊 Results
Sample output:

**Left to Right**: Original CT Image | Ground Truth Mask | Predicted Mask

![Segmentation Result](https://i.postimg.cc/fbq0GY9F/Screenshot-591.png)

## 📜 License
This project is for academic and research use only. Please comply with the LiTS Challenge data usage rules.
