# Head Pose Estimation

## Explanation of Approach

The overall approach to the problem can broadly be split into three main sections. First, there is the detection of the head/face in the images that are supplied. Secondly, we are extract 2-dimensional landmarks on the face at a number of keypoints. Once we have these keypoints, we use a 3-dimensional approximation of the face to estimate the pose of the head in 3-d described by a transition $t$ and a rotoational matrix $R$. This pose and 3-dimensional line from a suitable keypoint can then be used to describe the pose in terms of the 4 or 8 directions. Each of these stages will be descibed in detail in the sections below.

### Face Detection

### Landmark Detection

### Pose Estimation

## Dependencies

## Source Code

## Demo Video
