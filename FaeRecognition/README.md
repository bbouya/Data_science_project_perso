# Face Recognition

## Modern face recognition with deep learning and HOG algorithm

	1. Find Faces in image
	2. Affine Transformations 
	3. Encoding Faces (FaceNet
	4. Make a prediction ( Linear SVM

We are using the Histogram of Oriented Gradients method. Instead of 
computing gradients for every pixel of the image. We compute the weighted
vote orientation gradients of 16*16 pixels squares.
Afterward, we have a simple representation that capture the structure of a face.
