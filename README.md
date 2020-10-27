# Head Pose Estimation

The overall approach to the problem can broadly be split into three main sections. First, there is the detection of the head/face in the images that are supplied. Secondly, we are extract 2-dimensional landmarks on the face at a number of keypoints. Once we have these keypoints, we use a 3-dimensional approximation of the face to estimate the pose of the head in 3-d described by a transition  𝑡  and a rotoational matrix  𝑅 . This pose and 3-dimensional line from a suitable keypoint can then be used to describe the pose in terms of the 4 or 8 directions.

## Demo Video

https://drive.google.com/drive/folders/15dFgoeSjFGhnmyLcbawe_raJX0SpdvDC?usp=sharing
