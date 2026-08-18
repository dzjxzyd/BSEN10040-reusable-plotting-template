# BSEN41030 Reusable Plotting Template

A collection of reusable plotting examples and templates for data analysis and visualisation in science and engineering. The repository was prepared for **BSEN41030** teaching and demonstration activities.

## Contents

| Folder | Main examples |
|---|---|
| `AUC-ROC/` | ROC curves and AUC comparison |
| `bar-chart-demo/` | Bar charts using sample Excel data |
| `boxplot/` | Boxplots with and without individual data points |
| `confusion-matrix/` | Confusion matrices for multi-class results |
| `heat-map/` | Heatmaps for engineering, clinical and biological data |
| `histogram/` | Histograms for distributions and prediction scores |
| `predicted-actual-plot/` | Predicted-versus-actual plots and R² examples |
| `scatter-chart-demo/` | Scatter plots and t-SNE visualisation |

Each example folder contains a Python script and/or Jupyter Notebook, together with sample data and example output files.

## Getting started

Clone the repository and install the common dependencies:

```bash
git clone https://github.com/dzjxzyd/BSEN41030-reusable-plotting-template.git
cd BSEN41030-reusable-plotting-template

python -m venv .venv
source .venv/bin/activate        # macOS/Linux
# .venv\\Scripts\\activate       # Windows

pip install numpy pandas matplotlib seaborn scikit-learn openpyxl jupyter
```

Launch the notebooks with:

```bash
jupyter lab
```

Alternatively, run an individual Python example, for example:

```bash
python AUC-ROC/auc_roc.py
```

## Reusing an example

1. Choose the plotting folder closest to your application.
2. Replace the sample CSV or Excel data with your own data.
3. Update labels, colours, titles and output paths in the script or notebook.
4. Run the example and review the generated plot.

The examples are designed to be adapted rather than used as a single fixed package.

## File types

The repository includes:

- Python scripts (`.py`)
- Jupyter Notebooks (`.ipynb`)
- CSV and Excel input data
- PNG and PDF example figures

The examples use demonstration or synthetic data unless otherwise indicated. Generated cache files and operating-system metadata are intentionally excluded from the repository.
