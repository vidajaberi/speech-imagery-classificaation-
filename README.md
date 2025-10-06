# speech-imagery-classificaation-
# EEG Signal Windowing with MNE-Python

This repository demonstrates how to segment continuous EEG signals into fixed-length **time windows**  
. Windowing is a crucial preprocessing step for feature extraction  
and machine learning models applied to EEG data.

--------------------------------------------------------------------------------------------------------------------------------------------------------

## 📂 Notebook
- `windowing.ipynb` →  
  Steps included:
  - Load 2020 International BCI Competition  
  - Apply basic preprocessing (filtering, re-referencing)  
  - Define window length ( 1s)  
  - Split raw data into consecutive windows  
  - Store windowed data for further analysis  
  - Visualize example windows  

-------------------------------------------------------------------------------------------------------------------------------------------------------

## ▶️ How to Run
1. Install requirements:
   
   pip install mne numpy scipy matplotlib
   ---------------------------------------------
   Results & Algorithms
   The windowed EEG data was further analyzed with machine learning and deep learning algorithms.
   Machine Learning model:
   Support Vector Machine (SVM)

   Random Forest (RF)

   K-Nearest Neighbors (KNN)
   Deep learning models:
  

  Convolutional Neural Networks (CNNs)

   
