# TOP1-inhibitor-prediction
Standalone desktop applications for offline TDP1 inhibitory activity prediction using molecular fingerprints and machine learning models.

| Application      | Model                  | Fingerprint |
|------------------|------------------------|-------------|
| DNN_MACCS.exe    | Deep Neural Network    | MACCS Keys  |
| KNN_Morgan.exe   | K-Nearest Neighbors    | Morgan      |
| RF_Morgan.exe    | Random Forest          | Morgan      |
| SVM_Morgan.exe   | Support Vector Machine | Morgan      |

# Usage
1.	Double-click any .exe file to launch the application.
2.	Load a CSV file containing a column named SMILES.
3.	Click the "Run Prediction" button.
4.	Results will be saved in the same directory as the application.
# Input Format
Your CSV file must include a column header named exactly SMILES. Example:
SMILES
CC(=O)Oc1ccccc1C(=O)O
c1ccc2c(c1)cc1ccc3cccc4ccc2c1c34
# Requirements
•	Windows OS
•	No installation or additional dependencies required
