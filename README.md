# test1

UNet baseline notebook for the Data Science Bowl 2018 nuclei segmentation dataset.

## Files

- `unet-baseline (2).ipynb`: main training and inference notebook
- `requirements.txt`: Python package requirements for the notebook

## Local structure

- `input/`: place dataset zip files here
- `working/`: extracted data, checkpoints, and generated outputs

## Setup

```bash
python -m venv .venv
./.venv/bin/pip install -r requirements.txt
```

## Notes

- The notebook was adjusted to use relative paths instead of Kaggle-only paths.
- DataLoader workers are set up for notebook-safe execution on macOS/Jupyter.
