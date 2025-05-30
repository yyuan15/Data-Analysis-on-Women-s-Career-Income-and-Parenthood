# 👩‍💼 Data Analysis on Women's Career, Income, and Parenthood


## 🧠 Project Overview

This project explores the economic and demographic factors that influence women's career outcomes, with a specific focus on **personal income**. We apply econometric techniques to analyze how characteristics such as:

- **Age**
- **Race**
- **Marital status**
- **Education level**
- **Number of children**

affect women’s earnings in the U.S. labor market.

The goal is to provide quantitative evidence for understanding the structural and demographic determinants behind women's career trajectories.

## 🧪 Methodology

We use econometric tools, including:

- **Linear Regression**
- **Ordinary Least Squares (OLS) regression**
- **Multivariate multiple regression**
- **Empirical model building**
- **Robustness testing**

Our analysis is guided by economic theory and informed by prior research on gender income inequality and labor economics.

## 📊 Key Research Question

> What are the key demographic and familial factors that drive variation in personal income among working women in the United States?

## 📚 Data and Sources

We use microdata from a large-scale U.S. public-use dataset (`usa_00005.csv.gz`), which includes detailed records on:

- Personal and family income  
- Demographic traits (age, race, marital status, etc.)  
- Educational background  
- Number of children in the household  

> ⚠️ The dataset is large and tracked using Git Large File Storage (LFS).  
> Please ensure [Git LFS](https://git-lfs.github.com/) is installed before cloning this repository.

## 🧰 Python Packages Used

The following Python libraries were used for data analysis, modeling, and visualization:

```python
import pandas as pd                 # Data manipulation
import numpy as np                  # Numerical operations
import matplotlib.pyplot as plt     # Visualization
import seaborn as sns               # Statistical plotting
import statsmodels.api as sm        # Econometric modeling
import statsmodels.formula.api as smf  # Formula-based model building
from statsmodels.stats.outliers_influence import variance_inflation_factor  # Multicollinearity check
from stargazer.stargazer import Stargazer  # Regression summary tables
from IPython.core.display import HTML      # Enhanced HTML rendering in notebooks
import dask.dataframe as dd         # Parallelized data processing for large files
import warnings                     # Warning suppression
```

Install all dependencies with:

```bash
pip install pandas numpy matplotlib seaborn statsmodels stargazer dask
```

## 🚀 How to Run
1. Clone the repo
```bash
git lfs install
git clone https://github.com/yyuan15/Data-Analysis-on-Women-s-Career-Income-and-Parenthood.git
```
2. Open the notebook
 ```bash
   jupyter notebook Econ_320_Final_project.ipynb
```
