# Cell crops
Fiji macro to crop around individual cells. 
# Overview 
This macro segments cells using user-defined channel and gets bounding rectangles (Figure 1A) to save individual cells in a multi-channel image. Cells are saved as individual .tif files and an overlay of the segmentation for the whole image saved (Figure 1B). <br/> <br/>
![Picture1](https://github.com/SpillaneLab/Cell-crops/assets/143707918/f27f20d1-adb0-4919-ac5f-551bd2e52931) <br/> <br/>
Figure 1: A) Segmentation of membrane staining (left) used to get bounding rectangle of cell (right). B) Segmentation for whole image using membrane staining overlaid onto brightfield channel. 
# Installation 
Analysis performed using Fiji (Schindelin et al., 2012).
1.	Copy the code (from browser or download as .txt) and paste into macro window as: 
     Plugins > New > Macro
2.	Ensure the language is set to IJ1 Macro in the Language tab of the Macro window. 
3.	Save the macro using .ijm extension. 
# How to use 
1.	Adjust the method of segmentation as required – segmentation is required only to get bounding rectangle of the cell, not for quantification. 
# Authors 
Hannah McArthur – macros and description. 
# References
Schindelin, J., Arganda-Carreras, I., Frise, E., Kaynig, V., Longair, M., Pietzsch, T., Preibisch, S., Rueden, C., Saalfeld, S., Schmid, B., Tinevez, J.-Y., White, D.J., Hartenstein, V., Eliceiri, K., Tomancak, P., Cardona, A., 2012. Fiji: an open-source platform for biological-image analysis. Nat. Methods 9, 676–682. https://doi.org/10.1038/nmeth.2019


