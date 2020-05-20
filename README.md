# Face Detection

Face detection is a rather trivial computer vision problem. Here we are just trying to detect where a human face is rather than recognition of some human face.

The Machine Learning community is now at the stage where face detection is rather easy to implement using pre-trained models.
Some popular ones are-

  ### Haar Cascade
  ### MTCNN
 
These have been used in this project to detect faces in images.

## Haar Cascade-</a>
Haar Cascade classifier is a commonly used object detection algorithm. This method was proposed by Paul Viola and Michael Jones in their paper Rapid Object Detection using a Boosted Cascade of Simple Features( see link: https://www.researchgate.net/publication/3940582_Rapid_Object_Detection_using_a_Boosted_Cascade_of_Simple_Features)
The Haar Cascade model can be downloaded originally from- https://github.com/opencv/opencv/tree/master/data/haarcascades

## MTCNN
Multi-task Cascaded Convolutional Neural Networks(MTCNN) detects the bounding boxes of faces in an image along with their 5 Point Face Landmarks (link- https://kpzhang93.github.io/MTCNN_face_detection_alignment/paper/spl.pdf). 

## MTCNN vs Haar Cascade:
MTCNN was designed specifically for face detection and so it is no shock that MTCNN performed better that Haar cascade which has a more versatile use case.
For example: 

<img src='mtcnn_found.jpg'>

In the above image,Haar Cascade could not detect any face whereas MTCNN managed to find all.
## Installations needed:
```
      $pip install mtcnn
```
Also download Haar Cascade file from link: https://github.com/opencv/opencv/tree/master/data/haarcascades 
or from attached files.




