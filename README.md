# DS4002 CC3
This project is a case study that investigates whether incorporating clinical metadata (such as patient age and BI-RADS score) improves the performance of machine learning models for classifying breast ultrasound images as benign, malignant, or normal.

This project focuses on a comparative machine learning workflow:

Image-only model (using pretrained image features)

Image + metadata model (combining visual + clinical information)

The goal is to evaluate whether additional structured clinical information improves predictive performance and under what conditions it is most useful.

## Software and Platform
### Software used

Python 3.8+

Jupyter Notebook
### Required Packages
Install dependencies using:
```bash
pip install numpy pandas scikit-learn torch torchvision matplotlib seaborn
```
### Platform
This project is compatible with:

macOS
Windows
Linux

## Documentation
LISCENCE.MD: proper citation for repository

SCRIPTS folder: source code for project

DATA folder: initial data (imported test/training images and fruit labels) and final cleaned data

OUTPUT: figures and tables generated from scripts

SOURCES: sources used throughout project

## Reproducing Results
Launch Jupyter Notebook

 #### Open and run the notebooks in following order:

image_only_model.ipynb

image_plus_metadata.ipynb

evaluation_and_comparison.ipynb



#### The provided notebooks are starter templates. You are expected to:

Complete missing code sections

Train both models (image-only and multimodal)

Evaluate performance using standard metrics

Compare results and interpret findings



#### Generate Results

After running the notebooks, outputs will include:

Model performance metrics (accuracy, precision, recall, F1-score)
