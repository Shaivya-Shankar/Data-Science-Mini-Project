# Data-Science-Mini-Project

### Comparative analysis and optimization of hydropathy scales for predicting core interacting residues in protein–protein interfaces using CIRNet, deep learning, and machine learning models.

Worked collaboratively with researchers from Sapienza University and the University of Bristol to develop improved machine learning algorithms for predicting core interacting residues in protein-protein interfaces. The project utilized the CIRNet neural network architecture, incorporating shape, electrostatic, and hydropathy complementarity features for the classification of binding sites. We explored the impact of 28 different hydropathy scales, performed data normalization and feature engineering, and applied advanced techniques such as Principal Component Analysis (PCA) and hyperparameter optimization to enhance model accuracy. Key results included identification of optimal hydropathy scales and machine learning methods for robust interface residue prediction. 

#### Key contributions:

- Built and trained CNN and XGBoost models for core residue prediction in protein interactions

- Integrated and benchmarked multiple hydropathy scales using PCA and statistical analysis

- Improved accuracy through data pre-processing (power transformation, noise injection, min-max scaling)

- Contributed to a joint research pipeline and co-authored analysis between both universities

## Project Structure

- `Archive/` - Backup and previous versions of analysis or results.
- `codes/` - Python scripts and modules for model training, evaluation, and utilities.
- `dataset/` - Raw data files and processed datasets for experiments.
- `generated_data/` - Intermediate outputs and files generated during pipeline execution.
- `hydropathy/` - Hydropathy scale data, scripts, and related resources.
- `models/` - Saved model checkpoints, architecture files, and configuration.
- `notebooks/` - Jupyter notebooks for prototyping, visualization, and exploratory analysis.
- `Plots/` - Final plots and graphs for analysis results.
- `Plots_&_code/` - Scripts to generate plots with the output
- `static/` - Static assets, images, and files for documentation or presentation.
- `Comparative Analysis and Optimization of.pdf` - Full project report/documentation.
- `Presentation` - Slide deck for presenting project findings.
- `README.md` - Project overview and usage guide.
- `requirements` - List of dependencies for environment setup.

## Getting Started

1. Install dependencies with:  
   `pip install -r requirements`
2. Inspect data files in `dataset/`, and run scripts from `codes/` to preprocess or model data.
3. Use notebooks in `notebooks/` for exploration and benchmarking.
4. Generated output files will be stored in `generated_data/` and model results in `models/`.
5. Create or view analysis plots in `Plots/` and modify plot scripts in `Plots_&_code/`.

## Features

- CIRNet, CNN-based, and machine learning model implementations for protein interface prediction.
- Benchmarking and optimization of 28+ hydropathy scales.
- Full pipeline for feature preprocessing, model training, and result visualization.
- Datasets and plot generation scripts included for reproducibility.

## Results

- CIRNet and optimized hydropathy scale achieve state-of-the-art accuracy for binding residue prediction.
- Key results and figures included in `Plots/` and summary notebooks.

## License

This project is licensed under the MIT License.
