## Cognitive Restructuring in PTSD – Effective Connectivity Analyses
The repository contains de-identified effective connectivity data and the scripts used to support the main findings in the Agathos et al. manuscript. Analyses use the [SPM12 software package](https://www.fil.ion.ucl.ac.uk/spm) within MATLAB.

This study aimed to characterise alterations in effective connectivity of a thalamocortical brain network, centred on the mediodorsal thalamus, during cognitive restructuring of negative cognitions in PTSD relative to trauma-exposed controls. 

## Main Results
The [Run_PEB_and_LOOCV_Diagnosis_CNBT.m](Run_PEB_and_LOOCV_Diagnosis_CNBT.m) script will reproduce the main DCM results comparing effective connectivity between PTSD patients and trauma-exposed controls during cognitive restructuring (discussed in-text and visualized in Figure 4A).

## Supplementary Results
The [Run_PEB_and_LOOCV_Diagnosis_CNBT.m](Run_PEB_and_LOOCV_Diagnosis_CNBT.m) script will also reproduce the leave-one-out cross-validation (LOOCV) results predicting diagnostic status from modulation of MPFC-to-MDT connectivity during cognitive restructuring (Supplementary Figure SF1A).

The [Run_LOOCV_PTCI.m](Run_LOOCV_PTCI.m) script will reproduce the LOOCV results predicting posttraumatic cognitions in the PTSD group from modulation of MPFC-to-MDT connectivity during cognitive restructuring (Supplementary Figure SF1B-E).

## NOTES – IMPORTANT
Due to GitHub's system for storing large files, the GCM files which contain subject-level DCM estimates ([GCM.mat](GCM.mat) for the main DCM analyses; [PTSD_GCM_PTCI.mat](PTSD_GCM_PTCI.mat) for supplementary LOOCV analyses within the PTSD group) need to be downloaded separately and placed in the same directory as the .m script files.

To correctly download the GCM files, click on the file in the repository and click on either the 'Raw' or 'Download raw file' button. GCM files that are obtained by downloading the whole repository (e.g., as a .zip file) will not work.
