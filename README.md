# Additional Material for Epilepsy SISCOM Practical Session - AME 1

## Author: Marc Biosca

This project involves processing and normalizing MRI, ictal, and interictal SPECT images to localize the epileptogenic focus in a single subject.

## Files in this Repository
- *MarcBiosca_P7_Epilepsy.ipynb*: A Jupyter Notebook containing all operations, functions, and scripts used for processing, normalizing, and exploring the images. This includes steps like masking, normalization (mean, median, Z-score), and subtraction.

- *MarcBiosca_Poster_P7_AME1*: Scientific Poster titled *Multimodal Imaging Techniques in Epilepsy: A SISCOM-Based Approach* that goes through the steps in a ISCOM methodology using three types of normalization methods.

- *Resultant Images*:

1. *Atlas_in_MRI_space.nii.gz*: Harvard-Oxford cortical atlas transformed to the subject's MRI space.  
2. *masked_ictal.nii.gz*: Ictal SPECT image with the brain mask applied.  
3. *masked_interictal.nii.gz*: Interictal SPECT image with the brain mask applied.  
4. *normalized_mean_ictal.nii.gz*: Ictal SPECT normalized using mean normalization.  
5. *normalized_mean_interictal.nii.gz*: Interictal SPECT normalized using mean normalization.  
6. *normalized_median_ictal.nii.gz*: Ictal SPECT normalized using median normalization.  
7. *normalized_median_interictal.nii.gz*: Interictal SPECT normalized using median normalization.  
8. *normalized_z_ictal.nii.gz*: Ictal SPECT normalized using Z-score normalization.  
9. *normalized_z_interictal.nii.gz*: Interictal SPECT normalized using Z-score normalization.  
10. *RM_brain.nii.gz*: Skull-stripped brain extracted from the subject's MRI using FSL BET.  
11. *RM_brain_mask.nii.gz*: Binary brain mask extracted from the subject's MRI using FSL BET.  
12. *thresholded_mean_diff.nii.gz*: Thresholded subtraction image for mean normalization.  
13. *thresholded_median_diff.nii.gz*: Thresholded subtraction image for median normalization.  
14. *thresholded_z_diff.nii.gz*: Thresholded subtraction image for Z-score normalization.  

## Tools Used
- Python with nibabel and nilearn for image processing.
- FSL Library for brain extraction (BET) and registration (FLIRT).
- ITK-SNAP for visual inspection and verification.

For further details, contact Marc Biosca.
