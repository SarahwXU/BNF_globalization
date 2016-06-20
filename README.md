# Boundary Neural Fields Globalization

This is the code for Boundary Neural Fields globalization method. The technical report of the method can be found at http://arxiv.org/pdf/1511.02674v1.pdf 

If you use this software please cite our CVPR 2016 paper:

@InProceedings{gberta_2016_CVPR,<br />
author = {Gedas Bertasius and Jianbo Shi and Lorenzo Torresani},<br />
title = {Semantic Segmentation with Boundary Neural Fields},<br />
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},<br />
month = {June},<br />
year = {2016}<br />
}



## Installation

1. VL Feat

	Compile the VL Feat library in the folder 'libs/'

2. Normalized Cuts

	Compile Normalized Cuts code in the directory 'Ncuts_9/''

## Usage

To use BNF method with the boundary based affinities, check out the files 'BNF_binary_class_edge_affinity_demo.m' and 'BNF_multi_class_edge_affinity_demo.m' for binary and multi class segmentations respectively. If the boundaries are not available, you can use the demos 'BNF_binary_class_RGB_affinity_demo.m' and 'BNF_multi_class_RGB_affinity_demo.m', which perform our globalization technique using the RGB color affinities. 

## Notes

This version of the code is slightly different than the one presented in the technical report.
