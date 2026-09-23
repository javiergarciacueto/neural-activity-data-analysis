# Neural Activity Data Analysis

Python analysis of experimental neural activity using spike trains, firing rates, raster plots and correlation-based methods.

## Overview

This repository presents an exploratory analysis of experimental neuronal recordings. Spike times are aligned to different experimental events and compared across multiple trial conditions to study both individual-neuron and population-level activity.

The original analysis was developed as an academic project. The repository focuses on the data-analysis workflow and does not claim participation in experimental data collection.

## Analysis

The notebook includes:

- Raster plots aligned to context entry, inhalation and context exit.
- Firing-rate estimation.
- Individual-neuron and population-level visualizations.
- Comparisons across experimental conditions.
- Pearson correlation matrices between neurons.
- Exploratory response classification.
- Functional-network representations using NetworkX.
- Lagged cross-correlation analysis.

## Data

The analysis expects a CSV file with the following columns:

`Neurona`, `T_spike`, `Trial`, `T_entrada`, `T_salida`, `T_inhala`, `Ensayo`, `T_inicio`

The original dataset is not included here unless permission for public distribution has been confirmed.

To reproduce the analysis, place the appropriate dataset at:

```text
data/data.csv
```

## Repository structure

```text
neural-activity-data-analysis/
├── README.md
├── requirements.txt
├── notebooks/
│   └── neural_activity_analysis.ipynb
└── data/
    └── README.md
```

## Technologies

**Python** · **NumPy** · **Pandas** · **Matplotlib** · **Seaborn** · **SciPy** · **NetworkX** · **Jupyter Notebook**

## Notes

The notebook originated as an exploratory academic analysis. The public version preserves the analytical workflow while replacing environment-specific file loading with a repository-relative path.
