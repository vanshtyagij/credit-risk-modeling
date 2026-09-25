# Credit Risk Modeling

Open `Credit_Risk_Modeling.ipynb` in JupyterLab. No Flask, Streamlit or website is required.
s
## Run
1. Extract this ZIP.
2. Open JupyterLab in the extracted folder (Terminal: `jupyter lab`).
3. In the same Python environment as your Jupyter kernel run `pip install -r requirements.txt`.
4. Open the notebook and choose **Run > Run All Cells**.

## Data
The notebook creates **synthetic sample loan data** automatically; no download is necessary to run it. It is **not** real loan data, and its performance metrics must not be presented as real-world findings.

To switch to real data, obtain a properly licensed public dataset, e.g. LendingClub historical loan records, and independently prepare `data/loans.csv` with the exact columns described in the notebook. Use only features known when the loan application is submitted. Do not publish identifiable applicant data.

## Deliverables
EDA graphs, preprocessing, stratified train/test split, SMOTE on training folds, two classifiers, 5-fold cross-validation, confusion matrix, ROC and precision-recall curves, threshold analysis, permutation feature importance, optional SHAP code, responsible-use notes.

## Notes
The model is a portfolio demonstration, not a tool for actual lending decisions. For real deployment, conduct independent validation, fairness/privacy assessment and regulatory review.
