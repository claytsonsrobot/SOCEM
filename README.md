# SOCEM
SOCEM (Strength of Crops Extrapolation Machine) user information and software tools.

This repository is incomplete as of October 6th, 2022.

**The SOCEM and the flexural rigidity analysis method are patented.**
The patent title is: APPARATUS AND METHOD FOR HIGH THROUGHPUT MEASUREMENT OF LODGING RESISTANCE IN CROPS.
US patent application 17/465,623. Filed September 2, 2021.
Inventors: Robertson D.J., Stubbs C., Bebee A., Bennett G.C.

**CAD_3Dprint.zip:** This .zip file contains .STL and .SLDPRT files for the console screen container of the SOCEM, as well as additional accessories.

**thesis_ValidateSOCEM_Bennett_10142022.pdf:** A full pdf copy of my thesis which gives an overview of the backgroud for the device, step by step building instructions, and an analysis/discussion of results.   

**code_Arduino_SOCEM.zip:** This .zip file contains folders with the full arduino code for the Arduino Uno. Some libraries may need to be downloaded to run the code. Needed Libraries and the version of them used (some may not be the lastest versions) can be found as comments in the first few rows of the Main Arduino code. 

**CAD_lasercutWood.zip:** This .zip file contains .DXF and .SLDPRT files for the keyboard trap, Arduino storage box, and SOCEM console desktop stand. Text readme files are included with instructions. Note that dimensions of the Solidworks files are associated with text files, via the Solidworks equation manager.

**InstronMethods.zip:** This .zip file contains .im_ccyclic files which are meant to be run on BlueHill Instron data collection software, to determine the methods of automated operation for specimen testing. These methods have been optimized for testing wheat stems for hysteresis and for observing breakage, and applications extend beyond the scope of this project.

**images.zip:** This .zip file contains many .PNG and .JPG files which display the nature of the SOCEM device. Details include field use, component detail, software insight, and 3D renderings of SOCEM results.  

**objects3D.zip:** This .zip file contains .FBX files that retain a color-gradient and can be viewed using Microsoft 3D Viewer or a similar application. These are 3D models that provide insight into SOCEM performance by showing all 2021 data. There is a file for raw force data and a file for processed flexural rigidity data.

**code_MATLAB_STLgeneration.zip & code_Python_Blender_3Dmodeling.zip:** These .zip files contain code that can be used to generate 3D rendering of SOCEM data, as shown in **objects3D.zip**. The MATLAB scripts generate STL files, which are imported by Python and then distributed in three dimensions using Blender Python, with labels. A color gradient is applied, the procedural colors are baked, and then an FBX file is exported. 

