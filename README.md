# residual_thresholding

## **Data:**

1. ***meta-data***: folder containing the tomographic slices from which the crack network will be segmented.
2. ***Residual_Thresholding_Fiji_output***: folder containing the microfractures segmented in Fiji using the thresholds yielded by Residual Thresholding.
3. ***Skeletonisation_Fiji_output***: folder containing the microfractures segmented in Fiji from the binary images (segmenting cracks in white) yielded by Skeletonisation (the method that Residual Thresholding is compared to).
4. ***Cumulative_shear_strain_cropped_to_2D_CT_scans_for_Claudia.tif***: shear strain from which the thickness of the shear band is inferred. [used in *Shear_Band_Thickness**.ipynb*]
5. ***Evolution_GT_all.csv***: file containing the completeness magnitude and best-fit power-law exponent of the crack length distribution in each image segmented with Residual Thresholding. [used in *Completeness_Magnitude.ipynb*]
6. ***Evolution_SK_all.csv***: file containing the completeness magnitude and best-fit power-law exponent of the crack length distribution in each image segmented with Skeletonisation.[used in *Completeness_Magnitude.ipynb*]

## Code: 

1. ***Threshold_Calculation.ipynb***: Residual Thresholding method to find greyscale thresholds that segment microfracture network.
2. ***Shear_Band_Thickness.ipynb***: method that infers the thickness of the shear band.
3. ***Skeletonisation_analysis.ipynb***: shows how Skeletonisation algorithm is employed as a comparison to Residual Thresholding.
4. ***Crack_Length_Distribution.ipynb***: plots crack length distributions from data segmented by both Residual Thresholding and Skeletonisation.
5. ***Crack_Orientation_Distribution.ipynb***: plots crack orientation distributions from data segmented by both Residual Thresholding and Skeletonisation.
6. ***Completeness_Magnitude.ipynb***: method that finds the best-fit power-law exponent  and completeness magnitude to the microcrack length distributions.
