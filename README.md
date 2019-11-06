# Lip Extraction Framework

This is a Python function for extracting lip data from video files. The function takes a path to a video file and returns a 3D Numpy array of pixel data. The array consists of the lip region in each frame of video stacked together to form a 3D array.

This function makes use of the Dlib face recognition library, openCV, and Imutils for Dlib-Numpy compatibility. This function is available for any use both academic or commercial, no citation necessary.

In order for this function to work the Dlib 68 facial landmark dat file must be in the same folder as the lip detector function. The file is available here: https://github.com/AKSHAYUBHAT/TensorFace/blob/master/openface/models/dlib/shape_predictor_68_face_landmarks.dat

This function can be easily modified to return an array of different facial feature data such as the eyes or nose. This is done by modifying the Dlib facial landmarks used to extract the region of interest. The lip region corresponds to landmarks 48:68, as seen in the attached Dlib facial landmarks jpg.

![alt text](https://github.com/mattrochford/lip_extraction/blob/master/facial_landmarks_68markup-768x619.jpg
