# Online Retail: Data Cleaning, EDA and Interactive Dashboard (CA2)

CCT College Dublin · Data Visualisation and Communication · CA2

This repository holds a Jupyter notebook that cleans and explores the Online
Retail dataset (transactions of a UK-based online retailer, December 2010 to
December 2011) and builds an interactive dashboard for a sales manager.

## Data

The data is **not** included in this repository. To run the notebook:

1. Download `Online Retail.xlsx` from the CA2 assessment folder on Moodle.
2. Put it in the `data/` folder, so the path is `data/Online Retail.xlsx`.

## How to run

Requirements: Python 3, Jupyter, pandas, openpyxl (to read the Excel file),
numpy, matplotlib, seaborn, plotly and ipywidgets.

```bash
pip install pandas openpyxl numpy matplotlib seaborn plotly ipywidgets jupyter
jupyter notebook
```

Then open the notebook and run all cells from top to bottom. The dashboard
needs a running kernel, because the filters are ipywidgets.
