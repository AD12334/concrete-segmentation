# Concrete Crack Segmentation

A Python notebook project exploring concrete surface-crack segmentation with Ultralytics YOLO. The notebook downloads a crack-image dataset, prepares the data, and trains a YOLO segmentation model.

## Project notebook

[`CS4287-Assign2-23358173-23380039-23376295.ipynb`](https://github.com/AD12334/concrete-segmentation/blob/main/CS4287-Assign2-23358173-23380039-23376295.ipynb)

## Requirements

The notebook was verified with Python 3.10 on Windows 11. It installs these packages when run:

- Ultralytics
- split-folders
- kagglehub

It also uses NumPy, Matplotlib, OpenCV, PyTorch, and other dependencies installed with those packages.

## Getting started

1. Clone the repository and open the notebook in Jupyter Notebook or JupyterLab.
2. Run the cells from top to bottom. The notebook installs its dependencies and downloads the dataset using KaggleHub.
3. Follow the notebook's data-preparation and training cells.

Training a segmentation model can take a long time. A compatible GPU is recommended.

## Dataset

The notebook downloads the `arunrk7/surface-crack-detection` dataset via KaggleHub and saves it under `./content/surface-crack-detection`.

The notebook's introductory comment links to a different Kaggle dataset (`arnavr10880/concrete-crack-images-for-classification`). Check that the dataset described in the comments matches the dataset intended for the project.

## Notes

- Run the notebook from its first cell so that dependencies and data are prepared.
- Dataset downloads require an internet connection.
- Training duration depends on the available hardware and the notebook's model settings.