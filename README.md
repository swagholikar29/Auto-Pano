# Auto-Pano
Panorama Stitching using Classical Computer Vision

This repository implements classical approach for panorama image stitching. Classical Approach of image stitching uses corner detection, Adaptive non-maximal suppression, feature descriptor, matching and RANSAC.

<img src="Phase1/Data/Train/CustomSet1/1.jpg"   align="center" alt="Original" width="200"/> <img src="Phase1/Data/Train/CustomSet1/2.jpg"  align="center" alt="Undistorted" width="200"/> <img src="Phase1/Data/Train/CustomSet1/3.jpg"  align="center" alt="Undistorted" width="200"/>

<img src="Phase1/results/customset1/mypano.png" align="center" alt="Pano" width="600"/>

The path to the folder of images can be provided as mentioned below.

``python Wrapper.py --Folder $PATH_TO_DATA
``