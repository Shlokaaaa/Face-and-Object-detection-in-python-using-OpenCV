# Face-and-Object-detection-in-python-using-OpenCV

Aim : Compute a python code that performs face and object detection using open-cv. (along with detection we are also identifying the person)

Imported files : open-cv, face-recognition, numpy, math

Description : The face/object detection project uses the face-recognition packages to detect face and object that occur in the frame which are pre-built encoded using the prototxt and caffemodel files from the MobileNetSSD which are pre-built Neural Network files. With the help of these 2 files, we  detect any face or object that comes in the frame. This code moreover detects any object held by a person in the frame. The logic setup for this implementation is that if the mid point of the square boundary that we set for the object is 1000 pixels away from the mid point of the square boundary of the face detected, then a message ‘Person is holding an object’ is shown at the bottom right of the square of the respective face. 
