# Alzheimer’s Disease Classification from MRI Scans

This project aims to classify the stages of Alzheimer’s disease based on MRI scans using a Convolutional Neural Network (CNN) built on top of MobileNetV2. The model is trained to differentiate between various stages of Alzheimer's disease using labeled MRI scan data.

## Requirements
To run this script, the following packages need to be installed:
- `tensorflow` (or `tensorflow-gpu` for GPU support)
- `tensorflow-addons`
- `keras`
- `imblearn`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Install them using:
```bash
pip install tensorflow tensorflow-addons keras imblearn matplotlib seaborn scikit-learn
Script Overview
The script performs the following main tasks:

Data Loading and Preprocessing: Loads MRI scans, applies rescaling, and augments the dataset.
Model Building: Constructs a CNN based on MobileNetV2 for feature extraction, followed by fully connected layers for classification.
Training: Trains the model with a learning rate scheduler.
Evaluation: Evaluates the model’s performance using precision, recall, F1-score, and a confusion matrix.
Usage
Clone this repository.
Install the required packages as shown above.
Run the script:
python alzheimer’s_disease_classification_from_mri_scans.py
Results
The model outputs classification reports and a confusion matrix, providing insights into the model’s performance across different stages of Alzheimer's disease.

Notes
This script was designed to run in a Jupyter notebook and has been adapted to Python script format.
Modify paths as needed to point to your data directory.
License
This project is licensed under the MIT License.

---

This README should help set up the project for others using it on GitHub. If there are additional details or sections, such as dataset instructions, let me know! &#8203;:contentReference[oaicite:0]{index=0}&#8203;
