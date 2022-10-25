# joint-bolt-understanding-with-Edge-detection
This is a study to show that methodology developed for better edge detection via CNN shows better result than without data preprocessing
Abstract—The paper aims to identify the kind of joints and 
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
