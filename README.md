Face Detection and Recognition:

I have done this project with the OpenCV library of Python programming. The Face Recognition process is divided into three steps.

1. Prepare training data: I have used 12 images for each person and my training data contains in total of 24 pictures for two persons in two different folders. Then I have to prepare the training data because the OpenCV face recognizer accepts data in a specific format and after that, I use OpenCV's  LBP face detector to detect the face.

2. Train Face Recognizer: OpenCV comes equipped with three face recognizers and I initialized the Local Binary Patterns Histogram face recognizer because Eigenfaces and Fisherfaces face recognizer are affected by light and train the face recognizer by converting the labels vector into NumPy array.

3. Testing: I take the two images of two persons, detect faces from each of them, and then pass those faces to our trained face recognizer to see if it recognizes them.

