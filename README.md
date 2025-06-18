# PhD
# 🧠 Interactive Cell Segmentation with CellSAM

This repository provides an interactive pipeline for threshold-based preprocessing and segmentation of biological images using the CellSAM deep learning framework. The workflow includes image cropping, brightness adjustment, interactive thresholding, segmentation, and exporting results as TIFF masks and Excel summaries.

---

## 📂 Features

- Crop and preprocess PNG images
- Stretch image contrast dynamically
- Interactive threshold slider using `ipywidgets`
- Deep learning segmentation with `CellSAM`
- Object counting using connected component labeling
- Export results as `.tif` masks and Excel `.xlsx` summary

---

## 📦 Requirements

Install the required packages:

```bash
pip install -r requirements.txt
