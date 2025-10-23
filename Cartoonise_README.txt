Cartoonise-Video
Project to cartoonise any video with Image processing and Machine Learning
Computer Vision
Computer vision is a process by which we can understand images and videos how they are stored and how we can manipulate and retrieve data from them. Computer Vision is the base or mostly used for Artificial Intelligence. Computer-Vision is playing a major role in self-driving cars, robotics as well as in photo correction apps. 

Approaches used :
1.	Using OpenCV image processing capabilities.
The cartoonise.py file contains the code for simple cartooning the image with the use of Bilateral Filtering and edge detection using OpenCV.
OpenCV is the huge open-source library for computer vision, machine learning, and image processing and now it plays a major role in real-time operation which is very important in today’s systems. By using it, one can process images and videos to identify objects, faces, or even the handwriting of a human. When it is integrated with various libraries, such as NumPy, python is capable of processing the OpenCV array structure for analysis. To Identify image patterns and their various features we use vector space and perform mathematical operations on these features. 

 Here first the image's edge are detected and then bilateral filter are applied to it for its smoothening. Finally, both images are merged into one by taking the inverse Binary mask off the edges.
2.	Using the K-Means Clustering Algorithm from Machine Learning

The Cartoonise_Kmeans.py file contains the code for this implementation. In this approach, the image is flattened to an array then it is put to the K-means algorithm from which centers are found and finally these centers are used to segregate the different color regions in the image. This technique is basically used for Colour reduction in image processing.

The 5 Steps in K-means Clustering Algorithm
Step 1. Randomly pick k data points as our initial Centroids.
Step 2. Find the distance (Euclidean distance for our purpose) between each data point in our training set with the k centroids.
Step 3. Now assign each data point to the closest centroid according to the distance found.
Step 4. Update centroid location by taking the average of the points in each cluster group.
Step 5. Repeat Steps 2 to 4 till our centroids don’t change.
We can choose the optimal value of K (Number of Clusters) using methods like the Elbow method.

System Requirements: Python 3 , OpenCV, Numpy installed.
How to use this project
1.	Keep the pc wherever you want to cartoonise.
2. Run the python scripts given above according to preference.
3. Enjoy the effect.



 


  

