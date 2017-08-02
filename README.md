SegFlow
=========================================
Introduction
-----------------------------------------
This paper proposes an end-to-end trainable network, SegFlow, for simultaneously predicting pixel-wise object segmentation and optical flow in videos. The proposed SegFlow has two branches where useful information of object segmentation and optical flow is propagated bidirectionally in a unified framework. The segmentation branch is based on a fully convolutional network, which has been proved effective in image segmentation task, and the optical flow branch takes advantage of the FlowNet model. The unified framework is trained iteratively offline to learn a generic notion, and fine tuned online for specific objects. Extensive experiments on both the video object segmentation and optical flow datasets demonstrate that introducing optical flow improves the performance of segmentation and vice versa, against the state-of-the-art algorithms.

[SegFlow](https://www.overleaf.com/read/cjwvjvccrjwv) will be published at ICCV2017.


Citing SegFlow
------------------------------------------
If you find SegFlow useful in your research, please consider citing:


Contents
------------------------------------------

Code
------------------------------------------
