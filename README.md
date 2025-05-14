# PNG to HDF5 Converter with TITAN Model

This repository provides tools to convert `.png` image files into `.h5` (HDF5) format so that they can be processed by large language models (LLMs) or deep learning pipelines.

## 🔧 Features

- Convert individual or batches of `.png` images into `.h5` files
- Use the [TITAN model](https://github.com/mahmoodlab/TITAN) from Mahmood Lab @ Harvard/MGB to extract patch-level features
- Store features and coordinates in HDF5 format for downstream use

## 📁 Notebooks

- **`covert_h5.ipynb`**  
  Converts `.png` images into `.h5` files. The labels are inferred from the folder names.

- **`whole_book.ipynb`**  
  Uses the [TITAN model](https://github.com/mahmoodlab/TITAN) to extract features from image patches and saves them into `.h5` files.
