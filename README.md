# German Credit Risk Scoring System

An interactive, step-by-step Machine Learning notebook developed to predict credit default risk using the classic **German Credit Dataset** from Kaggle. This project is structured cell-by-cell to demonstrate data preprocessing, exploratory analysis, and model evaluation pipeline transparency.

## 🚀 Project Overview
* **Domain:** Financial Technology (FinTech) / Credit Scoring
* **Algorithm:** Random Forest Classifier
* **Format:** Jupyter Notebook (.ipynb) for modular execution
* **Core Libraries:** Pandas, NumPy, Scikit-Learn, Seaborn, Matplotlib

## 📊 Notebook Structure & Workflow
The notebook is documented cell-by-cell to show a clean machine-learning lifecycle:
* **Cell 1: Dependencies Setup** — Loading robust libraries (`sklearn`, `seaborn`, etc.).
* **Cell 2: Data Ingestion** — Reading the German Credit CSV data into a Pandas DataFrame.
* **Cell 3: Missing Value Handling** — Robust categorical imputation using the `'unknown'` tag strategy.
* **Cell 4: Feature Encoding** — Applying `LabelEncoder` over categorical types sequentially.
* **Cell 5: Dataset Splitting** — Implementing `train_test_split` to maintain evaluation hygiene.
* **Cell 6: Model Training** — Training an ensemble **Random Forest Classifier** with 100 estimators.
* **Cell 7: Model Evaluation Metrics** — Performance calculations for Accuracy, Precision, Recall, F1, and ROC-AUC.
* **Cell 8: Visualization Matrix** — Plotting an inline interactive Confusion Matrix Heatmap using Seaborn.

## 🛠️ Key Technical Focus
* **Metric Balance:** Focuses heavily on Precision and Recall over raw accuracy to prevent financial risks associated with misclassifying risky applicants.
* **Inline Visualization:** Employs explicit heatmaps to visually track predictive performance.

