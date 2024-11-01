# VWFA_Li
Repository For
> Li, J., Hiersche, K., Saygin, Z.M. (2024) Demystifying the Visual Word Form Area: Precision fMRI of Visual, Linguistic, and Attentional Properties of Ventral Temporal Cortex. https://www.biorxiv.org/content/10.1101/2023.06.15.544824v1
## Data Notes
psc_selectivity_data.mat contains two data structures
  - df includes psc data for fROIs created by different methods
      sig150: top 150 voxels for VTC regions
      sig150lmd: top 150 voxels for language and MD regions
      sig23: hard threshold (p<0.005) for VTC regions
      siglmg: hard threshold (p<0.005) for language and MD regions
      pctl10: top 10% voxels for VTC regions
      pctllmd: top 10% voxels for language and md regions
      vwfa_new150: top 150 voxels for the participants with the same scan parameters
      vwfa_new_wlmd: top 150 voxels for the participants with the same scan parameters with language and MD regions
      sig150_sm0: psc for top 150 voxels with unsmoothed data
  - vtcSEL contains category selectivity for VTC fROIs created by different methods (same fieldname names as above) (Figure 4)
timecourse_data.mat contains data for the timecourse plots
    vwfady: Figure 2 & 3
    lang: Figure 6
    for each fROIs, nTR x nConditions x nSubs
VTC_gradient_4categories_sig2.mat contains data for the VTC gradient plots (Figure 5)
** note, raw psc and psc with outlier removed (psc_noout) (reported in the manuscript) were both included
