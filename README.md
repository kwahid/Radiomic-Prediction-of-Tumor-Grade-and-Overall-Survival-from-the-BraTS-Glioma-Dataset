# Radiomic-Prediction-of-Tumor-Grade-and-Overall-Survival-from-the-BraTS-Glioma-Dataset
Folder corresponding to 2017 summer project at MD Anderson Cancer Center. 

## This repo contains the following files: 
PDF of project report (Radiomic Prediction of Tumor Grade and Overall Survival from the BraTS Glioma Dataset.pdf) <br><br>
PDF of supplementary information (Radiomic Prediction of Tumor Grade and Overall Survival from the BraTS Glioma Dataset SI.pdf) <br><br>
.csv files neccessary for grade classification task (grades_t1ce_label1_norm_binpt1_Wavelet_radiomics.csv, grades_flair_label2_norm_binpt1_Wavelet_radiomics.csv, grades_t1ce_label4_norm_binpt1_Wavelet_radiomics.csv) <br><br>
.csv files neccessary for survival classification task (Survival_t1ce_label1_norm_binpt1_Wavelet_radiomics_output.csv, Survival_flair_label2_norm_binpt1_Wavelet_radiomics.csv, Survival_t1ce_label4_norm_binpt1_Wavelet_radiomics_output.csv) <br><br>
Parameter file used in radiomic feature extaction (Params.yaml) <br><br>
Jupyter notebook of code implementation (Radiomic Prediction of Tumor Grade and Overall Survival from the BraTS Glioma Dataset.ipynb  <br><br>
HTML copy of Jupyter notebook <br><br>

## Utilized the following python libraries in project: 
pyradiomics to generate features of dataset. http://pyradiomics.readthedocs.io/en/latest/ <br><br>
pandas for data manipulation.<br><br>
sklearn for machine learning.<br><br>
imblearn for upsampling. <br><br>
matplotlib for graphing.<br><br>
seaborn for data visualizations. <br><br>
statsmodels for ANOVA statistical test. <br><br>
