# Brain-Tumor-Segmentation-and-Majority-Class-Classification
Academic team project developed for the Introduction to Machine Learning course, focusing on deep learning-based brain tumor segmentation and majority class classification using multi-modal MRI scans from the BraTS 2021 dataset.
# Brain Tumor Segmentation using Deep Learning (BraTS 2021)

## Overview

This project was developed as an academic team project for the *Introduction to Machine Learning* course. The goal of the project is to perform automated brain tumor segmentation using deep learning techniques on multi-modal MRI scans from the BraTS 2021 dataset.

The project focuses on preprocessing medical imaging data, training segmentation models, and visualizing tumor predictions to support AI-assisted medical image analysis.

---

## Dataset

This project uses the **BraTS 2021 (Brain Tumor Segmentation)** dataset, which contains multi-modal MRI scans including:

* T1
* T1ce
* T2
* FLAIR

The dataset also includes corresponding segmentation masks for tumor regions.

Dataset link:
https://www.med.upenn.edu/cbica/brats2021/

---

## Features

* Multi-modal MRI preprocessing
* MRI normalization and resizing
* 2D slice extraction from 3D MRI volumes
* Brain tumor segmentation
* Data visualization and mask plotting
* Deep learning model training using PyTorch
* Prediction and evaluation pipeline

---

## Technologies Used

* Python
* PyTorch
* NumPy
* Matplotlib
* NiBabel
* SciPy
* OpenCV

---

## Project Structure

```bash
├── data/
├── notebooks/
├── models/
├── outputs/
├── preprocessing/
├── training/
├── evaluation/
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/brain-tumor-segmentation.git
cd brain-tumor-segmentation
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

### Preprocess the Dataset

```bash
python preprocessing/preprocess.py
```

### Train the Model

```bash
python training/train.py
```

### Evaluate the Model

```bash
python evaluation/evaluate.py
```

---

## Results

The project aims to accurately identify and segment tumor regions from MRI scans using deep learning-based semantic segmentation techniques.

Example outputs may include:

* Original MRI slices
* Ground truth masks
* Predicted segmentation masks

---

## Learning Outcomes

Through this project, we explored:

* Medical image preprocessing
* Deep learning for image segmentation
* Handling 3D MRI data
* Model evaluation techniques
* AI applications in healthcare

---

## Contributors

Developed as a team project for the *Introduction to Machine Learning* course.


