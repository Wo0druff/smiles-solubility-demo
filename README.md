# Smiles Solubility Demo

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/Wo0druff/smiles-solubility-demo/blob/main/smiles_solubility_demo.ipynb
)

**AI for Drug Discovery — Predicting Molecular Solubility using SMILES**

This project demonstrates how artificial intelligence and cheminformatics can be applied to predict a key ADMET property — solubility — directly from molecular structure.  
It showcases practical skills in **machine learning, chemistry data processing, and reproducible research** — directly relevant to modern drug discovery pipelines.

## Overview
This project demonstrates how molecular solubility can be predicted directly from **SMILES representations** using cheminformatics descriptors and machine learning.  
It is designed as a simple, reproducible example for **drug discovery and computational chemistry pipelines**, and can be extended to other molecular property predictions.

## Key Features
- **Data source:** ESOL dataset (experimental solubility values).  
- **Descriptor generation:** automatic feature extraction from molecules using [RDKit](https://www.rdkit.org/).  
- **Machine learning model:** Random Forest regressor implemented in scikit-learn.  
- **Performance evaluation:** R² and RMSE metrics, plus visualization of predicted vs. real solubility values.  
- **Reproducibility:** ready-to-run Jupyter notebook in Google Colab.  

## Motivation
Predicting solubility is a **core step in drug discovery pipelines**, since solubility directly impacts absorption and bioavailability.  
This project shows how cheminformatics and machine learning can be combined into a lightweight, practical workflow — skills directly applicable to biotech and pharmaceutical research.  

## Results
- R² ≈ 0.7 (varies slightly depending on data split).   
- RMSE in line with literature baselines for ESOL.  
- Clear correlation between predicted and experimental solubility values.  

## How to Run
1. Click the **"Open in Colab"** button above.  
2. Run all cells — dependencies and dataset are automatically loaded.  
3. Explore or replace the dataset with your own SMILES-based data.  

## Next Steps
- Try alternative models (XGBoost, Neural Networks).  
- Integrate more advanced descriptors (e.g. Morgan fingerprints).  
- Apply the workflow to other ADMET-related properties.  

---

📌 **Note for recruiters / collaborators**:  
This project highlights hands-on skills in **Python, RDKit, scikit-learn, and molecular machine learning workflows**.  
It was built as part of my exploration into **AI for drug discovery** and demonstrates my ability to set up reproducible, applied data science experiments in cheminformatics.  
