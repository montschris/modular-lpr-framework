# Deep Learning-Based Modular Framework for Robust License Plate Recognition

This repository contains the official implementation accompanying our conference paper:

> **A Deep Learning-Based Modular Framework for Robust License Plate Recognition in Diverse Visual Environments**

Published in the **2025 9th International Artificial Intelligence and Data Processing Symposium (IDAP 2025).**

**DOI:** https://doi.org/10.1109/IDAP68205.2025.11222230

---

## 📖 Overview

This repository provides the implementation of a modular deep learning framework for robust License Plate Recognition (LPR) across diverse visual environments. The proposed framework integrates multiple computer vision techniques to improve recognition accuracy under challenging real-world conditions such as low resolution, varying illumination, and complex backgrounds.

The framework consists of the following modules:

- 🚗 License Plate Detection using **YOLOv8**
- 🔍 Image Super-Resolution using **Real-ESRGAN**
- 🔠 Optical Character Recognition (OCR)
- 📊 Performance Evaluation

---

## 📌 Repository Purpose

This repository contains the implementation used in our conference paper. It is intended for academic and research purposes, providing the codebase necessary to reproduce the proposed modular license plate recognition framework.

---

## 📄 Conference Paper

**Title**

*A Deep Learning-Based Modular Framework for Robust License Plate Recognition in Diverse Visual Environments*

**Conference**

2025 9th International Artificial Intelligence and Data Processing Symposium (IDAP)

**Authors**

- James Earl D. Cubillas
- Liezyl Jane F. Claros
- Kaye O. Dacua
- Christine Jay A. Montilla

**DOI**

https://doi.org/10.1109/IDAP68205.2025.11222230

---

## 📂 Project Structure

```text
.
├── Main_Code.ipynb          # Main notebook
├── data.yaml                # YOLO dataset configuration
├── requirements.txt         # Python dependencies
├── weights/                 # Model weights
├── data/                    # Input datasets
├── outputs/                 # Generated outputs
├── images/                  # README images
├── .gitignore
└── README.md
```

---

## ⚙️ Requirements

- Python 3.8 or later
- Jupyter Notebook or Google Colab
- CUDA-enabled GPU (recommended for training)

Install all required dependencies:

```bash
pip install -r requirements.txt
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/montschris/modular-lpr-framework.git
cd modular-lpr-framework
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the project

Open:

```text
Main_Code.ipynb
```

Execute the notebook cells sequentially.

---

## 🛠 Technologies Used

- Python
- YOLOv8
- Real-ESRGAN
- OpenCV
- EasyOCR
- NumPy
- Jupyter Notebook

---

## 📜 Citation

If you use this repository in your research, please cite our paper:

```bibtex
@INPROCEEDINGS{11222230,
  author={Cubillas, James Earl D. and Claros, Liezyl Jane F. and Dacua, Kaye O. and Montilla, Christine Jay A.},
  booktitle={2025 9th International Artificial Intelligence and Data Processing Symposium (IDAP)},
  title={A Deep Learning-Based Modular Framework for Robust License Plate Recognition in Diverse Visual Environments},
  year={2025},
  pages={1-5},
  doi={10.1109/IDAP68205.2025.11222230}
}
```

---

## 📬 Contact

For questions regarding this repository or the associated research, please contact any of the authors through their respective institutional or professional profiles.

---

## 📄 License

This repository is intended for **academic and research purposes**. Please cite the associated conference paper if you use this work in your own research.