# Analysis of the Cleveland Heart Disease Dataset

This project explores the **Cleveland Clinic Heart Disease dataset** using R and Python.

---

## Project Directories
- `Notebooks` → R markdown and Jupyter Notebook files
- `Data` → data used for the analyses   
- `Outputs` → rendered reports 

---

## Project Description
The Cleveland Heart Disease dataset contains patient information (age, sex, chest pain type, cholesterol, etc.) and a target variable indicating the presence of heart disease.
Dataset source: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)

This project takes two approaches to investigate the factors influence the development of coronary heart disease:
## 1. Statistical Analysis (R)
- Performed data inspection and cleaning  
- Tested for normality  
- Conducted **t-tests** for pairwise comparisons  
- Applied **ANOVA** with post-hoc tests  
- Measured associations using **Pearson's correlation**

### 2. Machine Learning Predictive Analysis (Python, scikit-learn)
- Performed data inspection and cleaning  
- Assessed feature importance using **information gain**
- Applied preprocessing: **one-hot encoding** for categorical features, **scaling** for numerical features  
- Built pipelines for multiple models: Logistic Regression, Naive Bayes, Random Forest, kNN  
- Evaluated models using **accuracy, precision, recall, F1 score, and ROC-AUC**

## View Reports

You can view the rendered HTML outputs directly in your browser:

- [Statistical Analysis Report](https://grace-ellen-pender.github.io/Heart-Disease-Analysis/Outputs/Heart_Disease_Statistical_Analysis.html)  
- [Machine Learning Report](https://grace-ellen-pender.github.io/Heart-Disease-Analysis/Outputs/Machine_Learning_Heart_Disease.html)

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Grace-Ellen-Pender/Heart-Disease-Analysis.git
   ```
2. Open the .Rmd file in RStudio (for the statistical analysis) or the .ipynb file in Jupyter Notebook (for the machine learning pipeline).

3. Install required packages (listed in the code, e.g., tidyverse, ggplot2, scikit-learn, pandas).

4. Place the dataset in the same folder as the code files if not already present.

5. Run all cells/chunks to reproduce the analysis.
