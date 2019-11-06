# Lip Extraction Framework

This is a Python function for extracting lip data from video files. The function takes a path to a video file and returns a 3D Numpy array of pixel data. The array consists of the lip region in each frame of video stacked together to form a 3D array.

This function makes use of the Dlib face recognition library, openCV, and Imutils for Dlib-Numpy compatibility. This function is available for any use both academic or commercial, no citation necessary.

This function can be easily modified to return an array of different facial feature data such as the eyes or nose. This is done by modifying the Dlib facial landmarks used to extract the region of interest. The lip region corresponds to landmarks 48:68, as seen in the attached Dlib facial landmarks jpg.
