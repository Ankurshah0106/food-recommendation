# Food Recommendation System

This repository contains a food recommendation project with multiple modeling approaches, synthetic data generation workflows, and project documentation.

## Project Overview

The project explores recommendation techniques for grocery/food product suggestions using:

- Clustering-based recommendation
- Deep Q-Network (DQN)
- Neural Collaborative Filtering (NCF)
- xDeepFM

Along with model experiments, the repository includes synthetic dataset generation notebooks, trained model artifacts, and supporting documentation.

## Repository Structure

- `Models/`: Model notebooks, trained model files (`.pkl`), and core grocery datasets
- `Synthetic Dataset/`: Notebooks and generated synthetic datasets used in experiments
- `Minutes/`: Team meeting minutes (PDF)
- `Main Report.pdf`: Full project report
- `User Manual.docx`: Usage documentation

## Key Files

- `Models/clustering_based_recommendation.ipynb`
- `Models/DQN (1).ipynb`
- `Models/neural_collaboritve_filtering_new.ipynb`
- `Models/xdeepfm_new.ipynb`
- `Synthetic Dataset/SyntheticData.ipynb`
- `Synthetic Dataset/synthetic_data_generator_intial.ipynb`

## How to Run

1. Install Python 3.8+.
2. Create and activate a virtual environment.
3. Install required libraries used by the notebooks, for example:
   - `pandas`
   - `numpy`
   - `scikit-learn`
   - `tensorflow` or `torch` (depending on notebook)
   - `matplotlib`
   - `jupyter`
4. Open notebooks in Jupyter and run cells in sequence.

Example:

```bash
jupyter notebook
```

Then open notebooks from `Models/` or `Synthetic Dataset/`.

## Notes

- Some trained model files (`.pkl`) are already included for reuse.
- If a notebook references local paths, update them to match your machine.
- For detailed methodology and results, see `Main Report.pdf`.

## Authors

Project by Group18 (CE903).
