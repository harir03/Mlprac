# Machine Learning Lab - Complete Experiments

**Army Institute of Technology, Pune**
Department of Electronics & Telecommunication Engineering
Subject: Machine Learning Lab (T.E., Semester I)

This repository contains all six experiments from the ML lab manual, implemented and executed in Jupyter / Google Colab notebooks. Every notebook includes the aim, theory, procedure, input data, program code, real executed outputs (console + graphs), observations, result and conclusion.

## Experiments

| No. | Title | Notebook |
|-----|-------|----------|
| 1 | Installation and Familiarization of Python Programming Environment using Google Colab | [EXP1_Python_Environment_Colab.ipynb](EXP1_Python_Environment_Colab.ipynb) |
| 2 | Visualize Engineering Datasets Using Graphs, Histograms and Scatter Plots with Matplotlib | [EXP2_Data_Visualization_Matplotlib.ipynb](EXP2_Data_Visualization_Matplotlib.ipynb) |
| 3 | Perform Data Pre-processing and Cleaning Operations on Real-World Datasets | [EXP3_Data_Preprocessing_Cleaning.ipynb](EXP3_Data_Preprocessing_Cleaning.ipynb) |
| 4 | Apply Feature Scaling, Normalization and Standardization Techniques Using Python Tools | [EXP4_Feature_Scaling.ipynb](EXP4_Feature_Scaling.ipynb) |
| 5 | Implementation of Linear Regression Algorithm for Prediction of Engineering Parameters | [EXP5_Linear_Regression_Concrete_Strength.ipynb](EXP5_Linear_Regression_Concrete_Strength.ipynb) |
| 6 | Develop Classification Models using Logistic Regression for Real-World Datasets | [EXP6_Logistic_Regression_Breast_Cancer.ipynb](EXP6_Logistic_Regression_Breast_Cancer.ipynb) |

## Open in Google Colab

Each notebook can be opened directly in Colab (no installation needed):

1. [Experiment 1 - Python Environment](https://colab.research.google.com/github/harir03/ml-lab-experiments/blob/main/EXP1_Python_Environment_Colab.ipynb)
2. [Experiment 2 - Data Visualization](https://colab.research.google.com/github/harir03/ml-lab-experiments/blob/main/EXP2_Data_Visualization_Matplotlib.ipynb)
3. [Experiment 3 - Data Pre-processing](https://colab.research.google.com/github/harir03/ml-lab-experiments/blob/main/EXP3_Data_Preprocessing_Cleaning.ipynb)
4. [Experiment 4 - Feature Scaling](https://colab.research.google.com/github/harir03/ml-lab-experiments/blob/main/EXP4_Feature_Scaling.ipynb)
5. [Experiment 5 - Linear Regression](https://colab.research.google.com/github/harir03/ml-lab-experiments/blob/main/EXP5_Linear_Regression_Concrete_Strength.ipynb)
6. [Experiment 6 - Logistic Regression](https://colab.research.google.com/github/harir03/ml-lab-experiments/blob/main/EXP6_Logistic_Regression_Breast_Cancer.ipynb)

Or: open [colab.research.google.com](https://colab.research.google.com) -> File -> Open notebook -> GitHub -> paste this repository's URL.

## Running locally

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
jupyter notebook
```

## Notes on data

- Experiments 1, 3, 4 and 6 use the exact input datasets given in the lab manual (Experiment 6 uses the built-in Wisconsin Breast Cancer Diagnostic dataset from scikit-learn).
- Experiments 2 and 5 use seeded simulated data exactly as specified in the manual (`np.random.seed(42)` / `default_rng(42)`), so all results are reproducible. The concrete-strength dataset in Experiment 5 is synthetic, generated from the physically realistic relation stated in the manual, and is labelled as such inside the notebook.
- All outputs shown in the notebooks are real executed outputs, including the graphs.
