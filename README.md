# GenePattern Data Preprocessing

This repository contains a Jupyter Notebook that performs preprocessing, statistical analysis, and visualization on gene expression data in the GCT file format, using tools commonly employed in the Mesirov Lab.

## Assignment Overview

The notebook performs the following tasks:

1. Defines a function to load GCT files into a Pandas DataFrame.
2. Loads and summarizes two GCT datasets.
3. Plots histograms for selected samples.
4. Calculates per-sample mean, median, and standard deviation.
5. Filters genes based on expression thresholds and re-calculates stats.
6. Plots histograms for the filtered dataset.

## How to Run

1. Install dependencies (if not already installed):
   ```bash
   pip install pandas matplotlib
2. Launch the notebook:
    ```bash
   jupyter notebook
4. Open GenePattern_GCT_Analysis.ipynb and run all cells.
