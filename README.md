# TESS Light Curve Classifier

## Project Summary

The goal of this project is to classify TESS light curves into distinct morphological categories associated with stellar variability of young stars (e.g., periodic, pulsating, binary, stochastic, etc.) using supervised machine learning techniques.

To achieve this, we:
- Computed a set of 28 statistical features from TESS light curves.
- Trained machine learning models using known classifications from [Rodriguez-Feliciano et al. 2023 (AJ 166, 189)](https://iopscience.iop.org/article/10.3847/1538-3881/acf865).
- Evaluated model performance and confusion matrices to assess classification accuracy.
- Created visualizations and animations to better understand class separability in feature space.

## Features and Data

To reproduce or expand this work, you will need:
- TESS light curves preprocessed and ready for feature extraction.
- The Python script `features_28.py`, originally developed by Bayron et al. (2023) and collaborators, which computes 28 light curve features essential for classification.

> Note: This repository includes trained model files and associated utilities for class prediction. Feature extraction must be performed prior to model usage.

## Usage

Instructions on how to:
- Extract features using `features_28.py`
- Load the trained models
- Predict morphology classes from your own light curves

will be added here.


## References

- Rodriguez-Feliciano et al. 2023, AJ 166, 189 [Link](https://iopscience.iop.org/article/10.3847/1538-3881/acf865)  

---

If you use this code or models in your own work, please give me a star and consider citing the references above and acknowledging this project.
