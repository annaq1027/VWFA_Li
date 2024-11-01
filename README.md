# VWFA_Li
Repository For
> Li, J., Hiersche, K., Saygin, Z.M. (2024) Demystifying the Visual Word Form Area: Precision fMRI of Visual, Linguistic, and Attentional Properties of Ventral Temporal Cortex. https://www.biorxiv.org/content/10.1101/2023.06.15.544824v1
# Data Structures Overview
## psc_selectivity_data.mat
This file contains two data structures:

### df
Includes psc data for fROIs created by different methods:
- **sig150**: Top 150 voxels for VTC regions
- **sig150lmd**: Top 150 voxels for language and MD regions
- **sig23**: Hard threshold (p<0.005) for VTC regions
- **siglmg**: Hard threshold (p<0.005) for language and MD regions
- **pctl10**: Top 10% voxels for VTC regions
- **pctllmd**: Top 10% voxels for language and MD regions
- **vwfa_new150**: Top 150 voxels for participants with the same scan parameters
- **vwfa_new_wlmd**: Top 150 voxels for participants with the same scan parameters with language and MD regions
- **sig150_sm0**: psc for top 150 voxels with unsmoothed data

### vtcSEL
Contains category selectivity for VTC fROIs created by different methods (same fieldname names as above) (Figure 4).

## timecourse_data.mat
Contains data for the timecourse plots:
- **vwfady**: Figure 2 & 3
- **lang**: Figure 6
- For each fROI: nTR x nConditions x nSubs

## VTC_gradient_4categories_sig2.mat
Contains data for the VTC gradient plots (Figure 5):
- **Note**: Raw psc and psc with outlier removed (`psc_noout`) (reported in the manuscript) are both included.

