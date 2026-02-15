# Real-Time Medical Image Analysis with Deep Learning

This repository contains deep learning experiments for CT scan image classification, focused on **COVID vs non-COVID** detection.

## Project Contents

- `CTSCAN/` - CT image dataset used for training and evaluation
  - `CTSCAN/COVID/` - 1240 images
  - `CTSCAN/non-COVID/` - 1195 images
- `dissertation.ipynb` - Main dissertation notebook
- `Densenet3.ipynb` - DenseNet-based model experiment
- `High of Densenetnew.ipynb` - DenseNet variant experiment
- `High of VGG16.ipynb` - VGG16-based model experiment
- `High of xception.ipynb` - Xception-based model experiment
- `High custom cnn.ipynb` and `high custom cnn(1).ipynb` - Custom CNN experiments

## Objective

Build and compare deep learning models for automated CT scan classification to support medical image analysis workflows.

## Setup

Use Python 3.9+ and create a virtual environment.

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install jupyter notebook tensorflow keras opencv-python scikit-learn matplotlib numpy pandas
```

## Run

```bash
jupyter notebook
```

Open the notebooks and run cells in sequence.

## Notes

- Notebook outputs and metrics may vary by hardware, library versions, and random seed.
- If any notebook uses absolute/local paths, update paths to match your environment.

## Author

Ankur Shah
