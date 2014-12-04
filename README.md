### OpenCV: Open Source Computer Vision Library

This is a fork of the OpenCV library (Release: 3.0-ocl-tp2) with the following modifications:

|Branch|Modifications|
|---|---|
|brisk-gray-values|The grayvalues during the BRISK feature descriptor extraction can be returned.|
|fixed-ransac-iterations|The RANSAC iteration count for the fundamental matrix estimation can be set.|

To use the two modifications, run:
```
git checkout brisk-gray-values
git checkout fixed-ransac-iterations
git checkout master
git merge brisk-gray-values fixed-ransac-iterations
```
then use the standard OpenCV build procedure.
