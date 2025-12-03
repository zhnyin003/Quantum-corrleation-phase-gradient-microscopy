# Quantum-corrleation-phase-gradient-microscopy

Code must be run on Labview 2020 or later. Main program is "Wavefront analysis Final.vi". 

The four zip files, "reference", "reference background", "Star target 200nm" and "Star target 200nm background" are sample data. The first two containing the coincidence data taken as reference and its corresponding coincidence background, the last two are coincidence data on a Star phase target of 200nm feature height. Each zip file contains 8 data files where each has coincidence data taken over 25 seconds. 

Unzip the data files into separate folders. Before running the Labview code, select the correspond file locations for each type of data file in the GUI. The code requires at least one file from each folder to be loaded. For best image quality, all files should be loaded - drag select all files when prompted by the program.


All program settings are already optimized for the sample data so no changes needs to be made.
- Centroid shift bound - Centroid shift cut off in pixels. Noise can sometimes result in very large centroid shifts
- Magnification - magnification of microscope system
- focal length - focal length of lens before camera in meters
- Beam diameter - Beam diameter on sample plane in millimeters
- Subtract background - whether background subtraction is performed
- Signal (Near Field) ROI - setting the region of interest in the signal beam in pixels

