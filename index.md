### Brief Intro:

**I am an exploration Geophysicist with 16 years of experience. I have developed practical skill and knowledge in integrated geoscience exploration activities, which primarily include seismic (2D and 3D) & non-seismic data acquisition, processing QC, structural & quantitative Interpretation and risk evaluation.**

**My journey to the world of Machine Learning & AI has already begun. Below is the list of some of the project programs developed previously.**

------------------------------------------------------------------------------------------

### Project 1: Gray Level Transformed Directional Normalized Standard Deviations (NSTD) for Edge Detection

**Link: https://github.com/sinhapm/GravMagGreyTransDirectionEdge.git**

**Scope of Program Field: Gravity, Magnetic & Remote Sensing Dataset**

_**Platform: MATLAB**_

The program calculates the Gray Level Transformed Directional Normalized Standard Deviations (NSTD) for Edge Detection.

It takes the 2D gridded points input (Irap Classic Points format) such as Input File Format (X(Integer) Y(Integer) Z(Float)) - XY in ascending order top to bottom direction of Input data: 1. West to East: Left to Right, 2. South to North: Top to Bottom

**Sample output image**

![](./assets/img/Image_GravLineament.jpg)

Open source Free Air Gravity data downloaded from the following site: https://topex.ucsd.edu/cgi-bin/get_data.cgi

------------------------------------------------------------------------------------------

### Project 2: Phase-Decomposition-3D-Seismic-Data-Odd-Even-Function-Method
**Matlab Program to perform the 3D seismic data Phase Decomposition based on Odd-Even function. It computes only the odd components (-90 degree, 90 degree) and the even components (+/-180 degree, 0 degree) from the 3D seismic data**.


**Link: https://github.com/sinhapm/Phase-Decomposition-3D-Seismic-Data-Odd-Even-Function-Method.git**

**Scope of Program Field: Attribute Analysis - 3D Seismic Phase Decomposition**

_**Platform: MATLAB(R2020), Opendtect 6.4**_

**Program file**: "**Test_run_codes_pdoed3D_sample_3Dseismic_matfile.m**" provided script reads the sample seismic input data ("**sample_3Dseismic.mat**") and calls the phase decomposition function scripts except two files (**od_doprocess.m** & **od_getparameters.m**) and display a Inline results. User can change the input parameters values and display the result.

For Opendtect Volume Builder: Except "Test_run_codes_pdoed3D_sample_3Dseismic_matfile.m" files, all other MATLAB ".m" required to be complied via MATLAB C Compiler to generate the c shared dll file.

Sample data ("**sample_3Dseismic.mat**") outputs test: script: "Test_run_codes_pdoed3D_sample_3Dseismic_matfile.m"

![](./assets/img//image_phasedecomposition.jpg)

------------------------------------------------------------------------------------------

### Project 3: On-Off-Amplitude-Analysis [Stacked Mean]
**The Program performs the on-off structural amplitude profiling based on common interval stacking.**

**Link: https://github.com/sinhapm/On-Off-Amplitude-Analysis---Stacked-Mean.git**

**Scope of Program Field: Attribute Analysis based on point data set of 3D seismic data structural interpretation - Interval Based Stacked Mean Amplitude Profiling**

_** Development Platform (Windows): Visual Basic**_

_** Utility Program : Stacked_Mean (Application file) / Setup file only**_

The program carries out the mean amplitude profiling of the 3D seismic point data set based on set interval. A ratio curve can be estimated by assigning the background level and same can be analysed with the know reference curve/s (maximum of 5 reference curves can be added). Reference curve/s can be shifted, stretched, squeezed along the x -axis.

**Sample image**:

![](./assets/img/Image_StackedMean.jpg )

------------------------------------------------------------------------------------------


