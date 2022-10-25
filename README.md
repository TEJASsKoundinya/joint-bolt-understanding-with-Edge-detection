# joint-bolt-understanding-with-Edge-detection
This is a study to show that methodology developed for better edge detection via CNN shows better result than without data preprocessing
<br />Abstract—The paper aims to identify the kind of joints and 
bolts in the most efficient way possible. A comparative study has 
been performed with and without edge detection where a 
convolution neural network (CNN) is used for classification of 
different joints and bolts present in an image. The image is 
provided as an input and is converted to grayscale format later 
applied edge detection into it. This is a part of image preprocessing which is compared with an image without any preprocessing techniques and where the result is compared between 
these two operations. Therefore, these classifications between 
the two neural networks are compared to find the best suited 
methodology for better results.
<br />III. METHODOLOGY
<br />The image of the structural joints in the PNG format is the 
primary input to the setup. PNG files are used to improve the 
resolution of the image thereby, preserving every pixel of 
color within an image and increasing the quality. The input 
given is converted to grayscale for understanding image 
processing better and easier visualization, and to overcome 
color and code complexity. This converted image undergoes 
the process of edge detection which allows users to observe 
the features of an image for a notable change in the gray level. 
This reduces the amount 0f data in an image and preserves 
the structural properties of an image. Normalization is used 
to ensure a similar distribution of data in the test image. All 
images of the data are color images and are cropped to 180 ×
180 for uniformity in the input. The CNN classifies the 
images using edge detection. The output is then predicted
after the classification occurs. 
<br />![Flowchart](https://user-images.githubusercontent.com/115657319/197710059-23ba2659-06a2-4acb-863e-79b11b4f7aee.png)
<br />Fig.1. Operational flowchart of methodology
<br />IV. ARCHITECTURE OF CNN
<br />![Slide1](https://user-images.githubusercontent.com/115657319/197709059-fed1cda0-4cbb-4204-a59c-755d613e6958.JPG)
<br />Fig.2. Architecture of CNN
<br />![summary of cnn](https://user-images.githubusercontent.com/115657319/197709587-c6c6301b-d5df-4acd-b4bc-21d85b4bfecc.jpg)
<br />Fig.3. Summary of CNN
<br />V. RESULTS AND DISCUSSION
<br />The difference between the two graphs is as shown below:
Fig. 4. Without Edge Detection
Fig. 5. With Edge Detection
Fig 4. Shows a graph without edge detection and Fig 5.
Shows a graph with edge detection. Without using the edge
detection test the accuracy got is around 97, and the
validation accuracy of around 75 whereas using edge
detection the training loss factor got is 0.15 and the validation
loss factor is 1.125. Using the edge detection method better
results have been achieved compared to the results achieved
without using edge detection. The model accuracy was found
to be similar in three spots hence it stopped training at 15
epochs. As the data is small of five different classes the
domain area is increased and the reprocessed image reduces
the complexity of the neural network.

Fig. 6. Wing Bolt With and Without Edge Detection
The above Fig. 6 shows an image of a wing bolt with and
without edge detection. It is noted that the accuracy of the
image without edge detection is around 56.21 percent and that
of the image with edge detection is 92.13 percent. Therefore,
this justifies that image processing is more accurate
comparatively.
<br />VI. CONCLUSION
<br />When the image is preprocessed, the CNN can classify better
when compared to the unprocessed image. Therefore, helps
in achieving better results. Object Detection is an emerging
technology in the field of Computer Vision and Image
Processing that deals with detecting objects of a particular
class in digital images. It has considered being one of the
most complicated and challenging tasks in computer vision.
Earlier several machine learning-based approaches like SIFT
(Scale-invariant feature transform) and HOG (Histogram of
oriented gradients) are widely used to classify objects in an
image. These approaches use the Support vector machine for
classification. The biggest challenges with these approaches
are that they are computationally intensive for use in realtime applications, and these methods do not work well with
massive datasets. To overcome these challenges, we
implemented a Deep Learning-based approach to
Convolutional Neural Networks (CNN) in this paper. The
Proposed approach provides accurate results in detecting
objects with a decent accuracy level. Hence, this paper
concludes that the accuracy of images with image processing
is higher and better than the latter.
