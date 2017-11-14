# Temporally Consistent Motion Segmentation from RGB-D Video

[Project Page](http://www.cgg.unibe.ch/publications/rgb-d-motion-segmentation/project-page)

In this repository we <will> share the data and code for the paper "Temporally Consistent Motion Segmentation from RGB-D Video" to be published in CGF. 

The repository is structured as follows:
### Data: 
Our RGB-D sequences are shared in the folder. We provide manually annoted ground truth segmentation for a set of frames. Please refer to the Wiki for data and annotation formats.
### Evaluation: 
Here we share matlab evaluation scripts for a quantitative evaluation of segmentations. Please refer to the Wiki for expected file formats encoding an obtained segmentation.
### Code: 
Here we share our C++ implementation of our motion segmentation approach. Please refer to our paper for details.
### Noisemodel: 
Here we share matlab scripts to fit noise models to sets of of depth frame  pairs. Please refer to our paper for details. To use our code with a new sensor you will have to extract a noise model first. For the Kinect for XBox One and the Asus Xtion Pro you can recylce the sensor description files shared with "one_chair" or "statue" respectively.

