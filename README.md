# TireDetection-Tracking
This repository contains a code for tire detection and tracking problem on pipeline.

Data is available in ./video_folder

Methods splitted into several parts:

- video_preprocessing for several preprocessing methods
- tire_trnsform for video_transformation, pipeline and object positioning and affine transforms of object into circular shapes
- background_subtraction with different pre and post processing techinques (kmeans, tresholding, morphologies)
- tire_detection for tire detection
- video_track for tire tracking

