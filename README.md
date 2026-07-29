

# Executives in Politics — Replication

## Overview

This repository contains a replication of selected empirical analyses from the paper:

**Babenko, I., Fedaseyeu, V., & Zhang, S. — "Executives in Politics."**

The replication was conducted in Python using a Jupyter Notebook. The analysis uses the datasets associated with the original study to reproduce selected descriptive statistics, figures, and regression results reported in the paper.

The replicated results were compared with the corresponding results reported in the original paper to assess the consistency of the findings.

## Research Objective

The objective of this project is to reproduce selected empirical results from the original study and evaluate whether the reported findings can be obtained using the available data and implemented analysis.

## Analyses Replicated

The notebook contains the following analyses:

* Descriptive statistics related to business politicians
* Figure 1: Business politicians and campaign spending
* Figure 2: Party affiliation of business politicians
* Figure 3: Business executives entering politics
* Figure 4: Campaign fundraising
* Figure 5: Legislative impact
* Table 3: Campaign fundraising regression analysis
* Table 7: Cumulative abnormal return (CAR) analysis
* Table 8: Committee assignment analysis
* Tables 11 and 12: Legislative voting analysis

## Repository Structure

```text
executives-in-politics-replication/
│
├── README.md
├── requirements.txt
│
├── executive.ipynb
│_____replication_results.md
```

### Files and Folders

**`executive.ipynb`**
Contains the complete Python analysis used for the replication.

**`data/raw/`**
Contains the input datasets required to run the analysis. Raw data are not included in the repository unless redistribution is permitted.

**`results/figures/`**
Contains figures generated from the replication analysis.

**`results/tables/`**
Contains tables and numerical results generated from the analysis.

**`docs/replication_results.md`**
Contains the comparison between the results obtained in this replication and the results reported in the original paper.

## Requirements

The analysis was implemented using Python and the following packages:

* Python 3.x
* pandas
* NumPy
* Matplotlib
* SciPy
* statsmodels
* openpyxl
* Jupyter Notebook

Install the required packages using:

```bash
pip install -r requirements.txt
```

## How to Run

1. Clone this repository.
2. Install the required Python packages.
3. Place the required datasets in the `data/raw/` directory.
4. Open `executive.ipynb` in Jupyter Notebook or JupyterLab.
5. Run the notebook cells sequentially.

The notebook generates the figures and statistical results used for the replication.

## Data

The analysis uses datasets associated with the original paper. The dataset we used from there paper is also attached.


## Replication Results

The replicated results were compared with the corresponding results reported in the original paper.

The comparison reports the replicated values, the values from the original paper, and any differences observed.

## Reproducibility

The repository is intended to make the replication analysis transparent and reproducible. The complete analysis is contained in `executive.ipynb`, while the repository structure separates the notebook, input data, generated results, and replication comparison.

## Citation

If you use this replication or its code, please cite the original paper and this repository.

## Authors

**Sai Kumar**

Replication project — *Executives in Politics*

