my approach in Grab-cut Image Segmentation represents a significant improvement over existing image segmentation methods and has potential to be applied in a wide range of computer vision applications such as medical imaging, autonomous driving and robotics. 
The goal of the image segmentation is to simplify and change the representation of an image into something that is more meaningful and easier to analyze. 
According to a human perception image segmentation is the process of dividing the image into non- overlapping meaningful regions.
The main objective of image segmentation is to divide an image into many sections for the further analysis, so we can get the only necessary or a segment of information. The partitioning the image will be based on some image features like color, texture, pixel intensity value etc. 
There are several techniques of image segmentation like thresholding method, region based method, edge based method, clustering methods and the watershed method. In this paper we will see some segmentation methods and what are the necessary things we should know while doing segmentations. 
We will also check some papers and analyze which method is best for image segmentation. Keywords: perception, segmentation, texture, edge, clustering.

Image segmentation is a most important part in the image processing in computer vision, it is used almost everywhere to process the images so our model should be able to recognize what’s inside the image. 
The segmentation splits the image into many sections or objects. The level to which the splitting the image is being carried rely on the problem is which has been solved.
When the object of an image has been segregated, segmentation should stop on that time.
The purpose of image segmentation is to simplify the image data into more meaningful and manageable information for further analysis.
For example we have an image so our aim is to recognize the objects into the image, for that we segment the image the details should be visible so our model work if there is a presence of an outliers or the paths aren’t clear or broken. 
It’s of no use to segment the image if  it may not be able to identify those elements.
The base of an image segmentation is having two basic properties. Either it will be discontinuity or likewise. 
