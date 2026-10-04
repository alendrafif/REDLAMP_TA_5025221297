# REDLAMP_TA_5025221297
## Informatics ITS Undergraduate Final Project Repository
## Alendra Rafif Athaillah (5025221297)

# Notebooks Description:
- `EDALH`: Notebook untuk Exploratory Data Analysis dan Penggabungan data mentah.
- `TA_Main`:Notebook untuk Hyperparameter Tuning
- `Scenario`: Notebook untuk Menjalankan Skenario dengan model hasil Hyperparameter Tuning

# Guide
> This project is divided into two notebooks. The main (TA_Main) functions as initial training and hyperparameter tuning. Once you have the parameters, input it into `scenario.ipynb`. Follow these instructions below:
## How to run TA_Main
- Execute Cell 1 (pip install), then wait for the installation to finish. Once it's done, change cell 1 into comment.
- afterwards, click "restart & clear cell output".
- then, click run all.
- Once the notebook has finished running, you can go to the hyperparameter tuning cell and copy or take notes of the best hyperparameter, which you can use in the scenario notebook.
## Panduan Menjalankan Scenario
- After acquiring the hyperparameters from `TA_Main`, you can set it on this notebook in cell 4 (Above the markdown "Dataset Loading").
- Execute Cell 1 (pip install), then wait for the installation to finish. Once it's done, change cell 1 into comment.
- afterwards, click "restart & clear cell output".
- then, set the window size that you want to use in the "windowing" section (cell 21), and set the number of pseudoanomaly classes that you want to generate in the augmentation phase (Cell 32)
- If you want to change FAA delta, change it in the apply_faa() function. The paper's default is 0.005.
