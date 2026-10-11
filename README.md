# BSEN10040 Reusable Plotting Template

A collection of reusable Python scripts, Jupyter notebooks, sample datasets, and generated figures for science, engineering, and food-and-health teaching examples.

## Included examples

| Folder | Example |
|---|---|
| `AUC-ROC/` | ROC curves and AUC comparison for multiple models |
| `bar-chart-demo/` | Bar charts from Excel data |
| `boxplot/` | Boxplots with and without individual observations |
| `confusion-matrix/` | Multi-class confusion-matrix visualisation |
| `heat-map/` | Heatmaps for biological, clinical, and engineering data |
| `histogram/` | Histograms for distributions and prediction scores |
| `predicted-actual-plot/` | Predicted-versus-actual plots and regression metrics |
| `scatter-chart-demo/` | Scatter plots and t-SNE visualisation |

Each example folder contains its current notebook and/or Python script, the required demonstration data, and any figures generated from the notebook.

## Installation

Clone the repository, create a virtual environment, and install the shared dependencies:

```bash
git clone https://github.com/dzjxzyd/BSEN10040-reusable-plotting-template.git
cd BSEN10040-reusable-plotting-template

python -m venv .venv
source .venv/bin/activate        # macOS/Linux
# .venv\Scripts\activate       # Windows

python -m pip install -r requirements.txt
```

## Using the notebooks

Start Jupyter from the repository root:

```bash
jupyter lab
```

Open the notebook in the example folder you want to use. The committed notebooks and figures reflect the versions prepared locally for this repository.

## Reusing an example

1. Choose the plotting folder closest to your application.
2. Replace the demonstration CSV or Excel file with your own data.
3. Update the input filename, column names, labels, colours, and title as needed.
4. Run the notebook or its companion Python script.
5. Review the generated plot before using it in reports or presentations.

Generated Python cache files and operating-system metadata are intentionally excluded from the repository.
