D3Impute: Dropout-aware Discrimination, Distribution-aware Modeling, and Density-guided Imputation for scRNA-seq data.

Usage Instructions      
MATLAB Users

For new datasets:

-Step 1: Run 00_Parameter.m to perform grid search and tune parameters. 

-Step 2: Run 01_D3Impute.m to perform imputation.

For existing datasets:

-Run 01_D3Impute.m to perform imputation.

Python Users

Run D3Impute.py to execute the imputation pipeline. The default demo dataset is Siletti. You may replace it with your own data.

Benchmarking & Visualization
MATLAB version includes:

- Clustering performance comparison across 13 algorithms (02_methodCompare.m)
- 14 types of visualizations, including t-SNE, error metrics, memory/runtime plots (03_Plot.m)
