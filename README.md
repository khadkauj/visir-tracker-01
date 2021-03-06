# Practical Assignment 1
**Dealine**: 26.02.2021

Please put your name here:  
**Name:** Ujjwal Khadka
## Problem 1.1
### Calculate Frames-per-Second (FPS) (Points 30)
1. Fork the current repository
2. Study the new framework-code of 
    - main.cpp
3. Check that the code is running correctly: it should show the video stream from the web-camera of your laptop.
4. Calculate average fps and print it to console every 2 seconds. Compare Debug and Release versions.

<ul><li>   Without face detection the fps goes upto 30fps both in debug mode and release mode. It was alos noted that fps 
reaches to 30 quicker than debug mode.</li>

<li>Release is faster than debug because Debug includes debug information in the compiled files (allowing easy debugging)
while Release usually has optimizations enabled.</li></ul>

### Note
MacOS users may need to launch the application with the administrator rights, to grant access to the web-camera.

## Problem 1.2
### Face detection (Points 70)
1. Read the OpenCV documentation about Viola-Jones face detector: [Cascade Classifier](https://docs.opencv.org/4.2.0/db/d28/tutorial_cascade_classifier.html)  
2. Implement face detection for the video stream from the web-camera using the ```cv::CascadeClassifier``` class.
3. Measure the FPS one more time. How FPS changed after incorporating the face detection into the framework?

<ul><li>With face detection fps goes upto 4 fps in 10 secs in debug mode which is very slow and in release mode goes upto 22fps within 10 secs.</li></ul>


### Note
Please do not copy-paste the example code from the OpenCV documentation, but try to understand the example code and implement the solution to the problem by yourself.

## Submission
Please submit the assignment by making a pull request.
**Important** : Please make sure that
- No _extra files_ are submitted (except those, which were mentioned in the assignment)
- The changes were made _only_ in those files where you were asked to write your code
- The Continiouse Integration system (appVeyor) can build the submitted code
- The rendered images are also submitted in the folder "renders" 

