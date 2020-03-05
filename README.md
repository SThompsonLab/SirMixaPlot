# SirMixaPlot
A collection of ImageJ and R functions for parsing extracting and analyzing datasets from microscopy images.

1) **SirMixaPlot - version 8.2 (Danger! High Voltage)** takes inputs from the YggData.ijm macro Be sure to read the comments for changes from the earlier versions (specifically from version 7). To begin from YggData csv's, run *imaGen()* within the directory containing the Nuclear and WholeCell directories generated by YggData. This will generate Nuclear (NUC), WholeCell (WC), and joined (WN) ROIs csv files that are in the right format for running *sirmixaplot(*csv*)*. 

2) **YggData - version 1.0 (World Tree)** takes any number of mircscopy images within a folder and generates ROI data. Two folders are created: Nuclear and WholeCell. Running the macro asks you to select the DAPI image first, which is used to extract nuclear information from all the images in the folder. The macro then iterates through each image and analyzes them independently for nuclear-independent data extraction. Depending on the magnification and staining intensity of your images, intensity and size thresholds, as well as watershedding, may need to be edited from the original macro. **YggData.ijm was written to work with ImageJ Fiji (downloaded 2020.01.15 from https://imagej.net/Fiji).**
