This is A face recognition Attendance system using Python Which involes different Machine Learning Algorithm namely Haarcascade and LBPH which are used for Detection And For the Range . From How many meters it can recognize the person 
Its accuracy is 75-82 %


The Haarcascade_frontalface_alt XML is a machine learning model used for detecting frontal faces in images or video.

Haar-Cascade Algorithm

It is based on Haar-like features and is commonly used in computer vision applications for face detection. The XML file contains the trained parameters of the model, which can be loaded into various programming frameworks such as OpenCV for use in face detection algorithms.


Local Binary Pattern Histogram (LBPH)

Local Binary Pattern Histogram (LBPH) is a simple yet very efficient texture operator which labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number . It was first described in 1994 (LBP) and has since been found to be a powerful feature for texture classification. 
It has further been determined that when LBP is combined with histograms of oriented gradients (HOG) descriptor, it improves the detection performance considerably on some datasets. The Local Binary Pattern is used for face recognition, which means identifying the captured image against the image already stored in the database. The algorithm makes use of four main parameters to recognize a face. The Local Binary Pattern is applied to the image and compared against the central pixel of the image, then we calculate the histogram value for the image

OpenCV

OpenCV, short for Open Source Computer Vision Library, is an open-source computer vision and machine learning software library. Originally developed by Intel, it is now maintained by a community of developers under the OpenCV Foundation.

In this article, we delve into OpenCV, exploring its functionalities, applications, and practical examples.

OpenCV  
Introduction
Opencv is a huge open-source library for computer vision, machine learning, and image processing. Now, it plays a major role in real-time operation which is very important in today’s systems. By using it, one can process images and videos to identify objects, faces, or even the handwriting of a human.

When it is integrated with various libraries, such as NumPy, python is capable of processing the opencv array structure for analysis. To Identify an image pattern and its various features we use vector space and perform mathematical operations on these features. 
