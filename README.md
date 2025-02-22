# Tree Growth Analysis – Effects of Growth Regulators

## Overview
This project analyzes a dataset from a study published in the *Canadian Journal of Statistics (September 1995), which examines the effects of **Paclobutrazol (PP 333)* and *Flurprimidol (EL-500)* on the growth of trimmed Silver Maple trees. The goal is to understand how these growth regulators impact *sprout length, internode number, and internode length*.

## Dataset
The dataset (cjs.csv) contains measurements of tree growth after applying different chemical treatments. Key columns include:
- *Sprout Length:* The total length of new terminal sprouts.
- *Internode Count:* The number of internodes formed per sprout.
- *Internode Length:* The average length of individual internodes.
- *Treatment Type:* The type of chemical treatment applied (PP 333, EL-500, or control groups).

## Methods
The project involves:
1. *Data Preprocessing:*
   - Handling categorical variables using LabelEncoder.
   - Identifying missing values and data inconsistencies.
2. *Exploratory Data Analysis (EDA):*
   - Summary statistics and dataset structure (pandas & numpy).
   - Visualizing distributions using seaborn and matplotlib.
   - Generating an automated data report using ydata-profiling.
3. *Clustering Analysis:*
   - Performing *K-Means clustering* to group trees based on their growth characteristics.
   - Applying *Principal Component Analysis (PCA)* for dimensionality reduction.

## Requirements
To run the analysis, install the necessary Python packages:
bash
pip install pandas numpy seaborn matplotlib scikit-learn ydata-profiling


## Running the Analysis
1. Clone this repository:
bash
git clone https://github.com/yourusername/tree-growth-analysis.git
cd tree-growth-analysis

2. Run the Jupyter Notebook tree_growth_analysis.ipynb.
3. View the automated data profiling report in a Jupyter Notebook output.

## Results & Findings
The analysis explores how growth regulators influence tree development and whether they effectively reduce excessive sprouting. Further studies could apply advanced machine learning models for predictive analysis.

