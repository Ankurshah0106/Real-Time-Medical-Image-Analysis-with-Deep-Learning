# Real-Time Medical Image Analysis with Deep Learning

Deep learning project for CT scan image classification, focused on **COVID vs non-COVID** detection.

## Key Highlights

- Binary CT classification pipeline (`COVID` vs `non-COVID`)
- Multiple model experiments: DenseNet, VGG16, Xception, custom CNN
- Notebook-driven experimentation for training and evaluation
- Dataset included in repository for reproducible analysis

## Dataset

- `CTSCAN/COVID/` - 1240 images
- `CTSCAN/non-COVID/` - 1195 images

## Repository Structure

- `dissertation.ipynb` - Main project notebook
- `Densenet3.ipynb` - DenseNet baseline
- `High of Densenetnew.ipynb` - DenseNet variant
- `High of VGG16.ipynb` - VGG16 experiment
- `High of xception.ipynb` - Xception experiment
- `High custom cnn.ipynb` - Custom CNN experiment
- `high custom cnn(1).ipynb` - Additional custom CNN run
- `CTSCAN/` - Image dataset

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

## Suggested Workflow

1. Start with `dissertation.ipynb` for overall pipeline.
2. Run architecture-specific notebooks for model comparisons.
3. Compare outputs (accuracy/loss/confusion matrix) across models.

## Notes

- Notebook outputs and metrics may vary by hardware, library versions, and random seed.
- If any notebook uses absolute/local paths, update paths to match your environment.

## Author

Ankur Shah
