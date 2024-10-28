# Akihiro-Matsumoto

The datasts for 2P GABA imaging by using iGABASnFR2 (Matsumoto et al. 2024, bioRxiv, https://www.biorxiv.org/content/10.1101/2024.01.09.574952v1).
Including:
1) dsets_ResponseMasures.mat:
   1-1) Response measurements for 49 groups (ON response index, OFF response index, Bi-response index, Transience index, and latency index).
   1-2) GABA signal
   1-3) RF size
2) dsets_MotionResponseMeasures.mat:
   2-1) Direction selectivity index (DSI)
   2-2) Orientation selectivity index (OSI)
   2-3) Motion/Flash preference index (M/F)
   2-4) Speed tuning index
3) dsets_NoiseCorr.mat:
   3-1) Noise corerlation and distance between ROIs in the same and different groups
4) dsets_ResponseMatrix.mat:
   4-1) response matrix for 49 groups (DSI, OSI, M/F, Speed tuning, Contrast modulation, Temporal frequency modulation)
5) dsets_FeatureScore.mat:
   5-1) feature scores for determined 30 informative groups (DSI, OSI, M/F, Speed tuning, Contrast modulation, Temporal frequency modulation)

6) scripts and data
   6-1) PF mapping. Matlab scripts and demo datasets for projective field (PF) mapping. Details are shown in "README.txt"
   6-2) R scripts for dot plots moleculary clustering (Figure 4)

7) Overview_49groups.xlsx:
   7-1) Summary of characterized GABA signal groups. Related to Extended Data Table 1
