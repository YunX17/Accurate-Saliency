
******************************************************************************************************************

The code is tested on windows 10 with MATLAB R2016b, CUDA 8.0
******************************************************************************************************************


Installation:
 

set up Caffe, check that Caffe MATLAB wrapper is set up correctly and make sure the path of file "caffe_.mexw64" has been correctly set up.

The code(mdf) of paper "Visual Saliency Based on Multiscale Deep Features" in CVPR 2015 and the code of paper "Edge Boxes: Locating Object Proposals from Edges" in ECCV 2014 are used for our saliency detection method. 

We advise you to use the code "Edge Boxes" in our zip file since the code has been changed for fitting the input in our code well.

As for the code "mdf", our zip file excludes it because of the large size. However, we provide a small video sequence example in the public Davis2016 dataset, including mdf results and EdgeBoxes results so that you do not need to use the code "mdf".

If you need to run other examples, please download the code "mdf" and note that the code can only detect an image at a time.
So a few changes is needed to adapt the video input.
It should be also noted that we ignore the line "esmap = 1.0./(1+exp(-10.0*(double(esmap)-0.5)));" in file "mdf_demo.m".

Usage:
 

1. Mdf results should be copied to the path ".\mdfColorSaliencyResult\" and make sure they are JPG files.
2. EdgeBoxes results should be copied to the path ".\edgeBoxProposalResult\".



Thank you

Best Regards




