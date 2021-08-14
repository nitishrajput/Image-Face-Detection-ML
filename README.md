# Image-Face-Detection-ML
Face Recognition in an Image using Machine Learning

Ever wondered how all the major social platforms like Facebook, Instagram detect faces in the images we upload? It is all done using Machine Learning algorithms through OpenCV to detect faces in the image.

Because faces are so complex, there is no one easy test that can tell you whether or not it detected a face. Instead, hundreds of little patterns and characteristics must be matched. The algorithms divide the effort of recognizing the face into hundreds of smaller, manageable tasks. These tasks are also called CLASSIFIERS. You may have 6,000 or more classifiers for something like a face, all of which must match for a face to be detected (within error limits, of course).To get around this, OpenCV uses cascades. 

I just tried to detect faces in an image by training a model that would do so by first converting the RGB image to a greyscale image and then run cascades on it. I would further extend this model to detect faces through live stream from the webcam.
