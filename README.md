# Fibril Probability Prediction

This repository contains two Jupyter Notebooks focused on predicting fibril structures in amyloid proteins and visualizing probability distributions.

## Contents

1. `fibril_prediction.ipynb`: This notebook covers the fibril prediction process, employing an MLP model to train on the dataset. It includes functions for ESM2 embedding, cross-validation, and evaluation metrics.
2. `plot_probs.ipynb`: This notebook provides tools for visualizing probability distributions, assisting in the interpretation of model predictions and fibril likelihoods.

### Directory Structure

- **data**: Contains training and testing datasets used for the fibril prediction model.
- **trained_models**: Stores pre-trained models, along with any saved metrics or intermediate results.
- **plot_pred_probs**: Contains generated plots and images from probability visualizations.
- **all_seq_pred**: Stores prediction results for all possible sequences containing amino acids K, E, or F.
- **test_seq_pred**: Stores prediction results for specific sequences of interest.

## Requirements

- Python libraries: `keras`, `sklearn`, `torch`, `pandas`, `matplotlib`, `seaborn`, `tensorflow`, `joblib`.
- Data files should be placed in the `data` directory.
- Pre-trained models and metrics can be stored in the `trained_models` directory for reuse.

## Usage

1. **Fibril Prediction**:
   - Open `fibril_prediction.ipynb`.
   - Follow the code cells in sequence to train and validate the fibril prediction model, or load a pre-trained model.
   - Results will be saved in the specified directories.

2. **Probability Plotting**:
   - Open `plot_probs.ipynb`.
   - Run cells sequentially to load, process, and visualize probability data.
   - Adjustments to the plot patterns can be made using the defined functions.
   - Plots will be saved in the specified directory.
