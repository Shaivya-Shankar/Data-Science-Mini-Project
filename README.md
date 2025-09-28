# Data-Science-Mini-Project

Comparative analysis and optimization of hydropathy scales for predicting core interacting residues in protein–protein interfaces using CIRNet, deep learning, and machine learning models.

## Project Structure

- `Archive/` - Previous versions, old results, and legacy project files.
- `codes/` - Source code for running models, preprocessing, feature engineering, and utility scripts.
- `dataset/` - Raw and processed datasets, including mapping of residue pairs and associated labels.
- `generated_data/` - Output data and intermediate files produced during pipeline runs.
- `hydropathy/` - Hydropathy scale definitions, reference data, and scale computation scripts.
- `models/` - Saved model checkpoints, configuration files, and architecture definitions for CIRNet and other models.
- `notebooks/` - Jupyter and exploratory data analysis notebooks for visualization, benchmarking, and results interpretation.
- `Plots/` - Static plots and figures for project results.
- `Plots_&_code/` - Scripts specifically used to generate the plots and figures included in the `Plots` directory.
- `static/` - Supporting files such as images or stylesheets for documentation or presentation.
- `Comparative Analysis and Optimization of.pdf` - Project report, including detailed methodology and results.
- `Presentation` - PowerPoint or slideshow materials for academic or industry presentation.
- `README.md` - This documentation and project instructions.
- `requirements` - Python dependencies required to reproduce the environment.

## Getting Started

1. Clone repository and install dependencies:  
   `pip install -r requirements`
2. Use notebooks in `notebooks/` for exploratory analysis and to reproduce results.
3. Run scripts from `codes/` to preprocess data, train models, and compute hydropathy scales.
4. Store or access data in `dataset/` and intermediate results in `generated_data/`.
5. Save or load trained models from `models/`.
6. Visualize project outputs using code from `Plots_&_code/` and results in `Plots/`.

## Features

- CIRNet implementation for protein interaction site prediction.
- Extensive hydropathy scale benchmarking and PCA-derived unified scale.
- Modular code, organized for scalability and reproducibility.
- Ready-to-use datasets and scripts for feature extraction and model training.


