# Prostate-Zones-Peripheral-Zone-and-Transition-Zone-Atlas

General Info: In this project, a probabilistic atlas-based approach has been developed for prostate zonal segmentation using diffusion-weighted imaging (DWI). This repository contains the compressed NIfTI files (.nii.gz) of prostate and it’s both zones, peripheral zone (PZ) and transition zone (TZ) atlas. MRI data were processed using in-house developed routines in MATLAB® (MathWorks Inc., v2018, Natick, MA). 

Only the mid-gland region of the prostate was used for atlas. This includes, for each subject, approximately five slices, starting from the base where the bladder starts to disappear till the prostate apex. 

Statistical Atlas: It is the average intensity map of the prostate for all subjects used in atlas construction. Intensity value is scaled between 0 to 255. Statistical atlas should be used for registration of the prostate of the test subject to the atlas. Preferably affine or any other registration can be used. 
(Filename: Statistical_Atlas.nii.gz). 

Probabilistic Atlas: There are two probabilistic atlas 1) probability atlas for Peripheral Zone (PZ) and 2) probability atlas for Transition zone (TZ). These are map of probability values (between 0 to 1), for both zones, PZ and TZ separately for the structure in the statistical atlas. 
(File names: Probabilistic_Atlas_PZ.nii.gz and Probabilistic_Atlas_TZ.nii.gz)

For detailed information and to use these atlases, the paper can be downloaded from this DOI: https://doi.org/10.1016/j.cmpb.2020.105572 

Use of these atlas and method must be cited with the details as: 
Singh, D; Kumar, V; Das, C.J; Singh, A; Mehndiratta, A; “Segmentation of prostate zones using probabilistic atlas-based method with diffusion-weighted MR images”, Computer Methods and Programs in Biomedicine (2020), pp.1-10, DOI:10.1016/j.cmpb.2020.105572.
https://doi.org/10.1016/j.cmpb.2020.105572

 
For any detailed enquiry, please contact
Dr Amit Mehndiratta, Indian Institute of Technology Delhi, India
  Email: amit.mehndiratta@keble.oxon.org

Disclaimer: These atlases can be used only for research purposes. Authors are not liable for any clinical use of it, authors could not held be responsible.
