# Group09_Retinal-OCT_CSE475
Retinal OCT
# Group
Kaniz Fatema Tuli ID:2023-1-60-192

Jannatul Ferdous Shanta ID:2022-3-60-167

Abira Ahsan ID:2023-2-60-127
# Dataset
OCTDL: Optical Coherence Tomography Dataset

Dataset link: https://www.kaggle.com/datasets/orvile/octdl-optical-coherence-tomography-dataset/data
# Track
Track 1 . GNN
# How to Run the Code
# Requirements
Install the Python libraries listed in requirements.txt.
# Input Files

The Task 3 explainability notebook uses the following artifact files, produced by the Task 3 improvement/ablation notebook and located in the code/task3/Output/ folder:

1. final_gnn.pt : https://github.com/KanizFatema192/Group09_Retinal-OCT_CSE475/blob/main/code/task3/Output/final_gnn.pt
2. ablation_results.csv : https://github.com/KanizFatema192/Group09_Retinal-OCT_CSE475/blob/main/code/task3/Output/ablation_results.csv
3. task3_manifest.json : https://github.com/KanizFatema192/Group09_Retinal-OCT_CSE475/blob/main/code/task3/Output/task3_manifest.json
4. test_split.csv : https://github.com/KanizFatema192/Group09_Retinal-OCT_CSE475/blob/main/code/task3/Output/test_split.csv

All other notebooks (Task 1 EDA, Task 2 baselines, Task 2 proposed model, Task 3 improvement/ablation) read the OCTDL dataset directly from Kaggle input and do not require any file from this repository.

# Running the Notebooks
Open the notebook from the code/task1/, code/task2/, or code/task3/ folder.
Make sure the dataset path and (for the explainability notebook) the CSV/artifact file paths are correct.
Run all cells from top to bottom.

# Dependencies

The notebooks were developed using the Kaggle Notebook environment with standard Python libraries (torch, torchvision, torch-geometric, scikit-learn, pandas, numpy, scipy, imbalanced-learn, statsmodels, xgboost, lightgbm, shap, lime, scikit-image, plotly, seaborn, umap-learn).

# Hardware

Kaggle GPU (Tesla T4 / P100).
# Result
