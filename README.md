# Dynamic Mode Decomposition for Real-Time Background/Foreground Separation in Video


## Overview

Dynamic Mode Decomposition (DMD) has arisen as an incredibly value tool in decomposing nonlinear systems in order to model underlying dynamics. DMD offers a different set of modes than other dimensional reduction methods, such as singular value decomposition (SVD) and principal component analysis (PCA) in that DMD offers oscillatory time resolution of the underlying modes, such that each mode contains both spatial and temporal information.


## Dataset

http://jacarini.dinf.usherbrooke.ca/dataset2012

We have used the highway.zip dataset from the above link.
The dataset consists of fast moving cars across a straight road.
We have selected 30 images out of a total of 1700 frames for our projects purpose 


## Results

![Screenshot](https://github.com/Abhinav-974/DMD-ML-Grp-3-Project/blob/main/Input_Data/in000051.jpg)

**Original Image**

The above image is deconstructed into its corresponding two components the (low rank) background and the (sparse)foreground

|Reconstructed Image|Background Image|Foreground Image|
|:-:|:-:|:-:|
|![Reconstructed Image](https://github.com/Abhinav-974/DMD-ML-Grp-3-Project/blob/main/Results/Reconstructed_Images/in000051.jpg)|![Background Image](https://github.com/Abhinav-974/DMD-ML-Grp-3-Project/blob/main/Results/Background_Images/in000051.jpg)|![Foreground Image](https://github.com/Abhinav-974/DMD-ML-Grp-3-Project/blob/main/Results/Foreground_Images/in000051.jpg)|
