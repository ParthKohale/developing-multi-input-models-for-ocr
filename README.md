# Multimodal OCR Classification

Hi, This is Parth Kohale, the one who made the project, I have been buidling and making deep learning related stuff for more than a year now but never took the efforts to actually post these projects so here goes probably something or nothing.. Enjjoyy your day, and if you have any suggestions please go ahead and let me know, i will be glad! Thank you, bye!

## Overview

This project focuses on developing a multimodal Optical Character Recognition (OCR) classification model using deep learning techniques in PyTorch. The model combines image data and categorical metadata to classify ID document categories extracted from scanned insurance documents.

The project demonstrates how multiple input modalities can improve OCR-based document classification performance in real-world insurance processing systems.

---

## Features

* Multi-input deep learning architecture
* OCR image classification pipeline
* Integration of image and categorical data
* PyTorch-based implementation
* Document category prediction for insurance IDs

---

## Technologies Used

* Python
* PyTorch
* NumPy
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Dataset

The dataset contains scanned insurance document images along with associated metadata used for OCR classification tasks.

---

## Project Structure

```bash
main_folder
│
├── data/
│   └── ocr_insurance_dataset.pkl
│
├── notebooks/
│   └── notebook.ipynb
│
├── src/
│   └── project_utils.py
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Model Architecture

The OCR model was designed using a multi-input neural network architecture:

* Convolutional layers process document images
* Additional inputs process categorical insurance data
* Features are combined for final classification

This multimodal approach improves classification accuracy compared to single-input OCR systems.

---

## Results

The model successfully learned to classify scanned insurance ID categories using both visual and structured input features.

Key outcomes:

* Improved OCR classification capability
* Effective multimodal feature integration
* Robust processing of scanned document inputs

---

## Installation

Clone the repository:

```bash
git clone https://github.com/ParthKohale/multimodal-ocr-classification.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
notebooks/notebook.ipynb
```

---

## Future Improvements

* Deploy as a web application
* Add advanced OCR preprocessing
* Improve model accuracy using transformer architectures
* Integrate real-time document scanning support

---

## License

This project is licensed under the MIT License.
