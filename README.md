# Vehicle detection and counting 💡
Vehicle detecting and also counting are becomes growing important in a area of highway regulators. 
However,because of the various structure of vehicles, their detections remain challenging which directly influence in accuracy of a vehicle count.
The proposed technique uses the background subtraction method to discover forefront objects in video sequel. 
Several OpenCV techniques, including of a thresholding, the adaptive morphology operations, and hole filling are later applied in the series of detecting moving vehicles more accurately. 
At last, vehicle counting is done by utilizing virtual identification zones. The outcome of an Experiment shows the accuracy of the proposed counting systems is around 96%.

The main aim of our system is to detect the moments of vehicles by analyzing camera pictures with the help of computer vision. 
Vehicle counting process accepts the video from single camera & detects the moving vehicles and counts them. 
Vehicle detection and counting system on highway is developed using OpenCV image development kits.


## Computer Vision👀
Computer vision is a process by which we can understand the images and videos how 
they are stored and how we can manipulate and retrieve data from them. Computer Vision is 
the base or mostly used for Artificial Intelligence. Computer-Vision is playing a major role in 
self-driving cars, robotics as well as in photo correction apps.

## OpenCV👍
OpenCV is the huge open-source library for the computer vision, machine learning, and 
image processing and now it plays a major role in real-time operation which is very important 
in today’s systems. By using it, one can process images and videos to identify objects, faces, 
or even handwriting of a human. When it integrated with various libraries, such as NumPy,
python is capable of processing the OpenCV array structure for analysis. To Identify image
pattern and its various features we use vector space and perform mathematical operations on
these features.
The first OpenCV version was 1.0. OpenCV is released under a BSD license and hence 
it’s free for both academic and commercial use. It has C++, C, Python and Java interfaces 
and supports Windows, Linux, Mac OS, iOS and Android. When OpenCV was designed the 
main focus was real-time applications for computational efficiency. All things are written in 
optimized C/C++ to take advantage of multi-core processing.
It is the basic introduction to OpenCV we can continue the Applications and all the things in
our upcoming articles.

## BUILD A VEHICLE DETECTION SYSTEM USING OPENCV AND PYTHON 🚀
### We are all set to build our vehicle detection system! 
### We will be using the computer vision library OpenCV a lot in this implementation. Let’s first import the required libraries and the modules.
✔Keep the frames in a folder named “frames” inside your working directory. From that folder, we will import the frames and keep them in a list and then for data exploration let’s display two consecutive frames:

It is hard to find any difference in these two frames, isn’t it? As discussed earlier, taking the difference of the pixel values of two consecutive frames will help us observe the moving objects.

![image](https://github.com/BasavarajAili1/Vehicle-Detection-Counting-Using-OpenCV/assets/112578014/6c06cda8-638b-40fa-8707-01482c4bff2f)

✔Now, the moving objects (vehicles) look more promising and most of the noise (undesired white regions) are gone. However, the highlighted regions are a bit fragmented. So, we can apply image dilation over this image:

![image](https://github.com/BasavarajAili1/Vehicle-Detection-Counting-Using-OpenCV/assets/112578014/ea78a65b-e62a-49a5-befa-d02f90d10365)

✔The moving objects have more solid highlighted regions. Hopefully, the number of contours for every object in the frame will not be more than three.
However, we are not going to use the entire frame to detect moving vehicles. We will first select a zone, and if a vehicle moves into that zone, then only it will be detected.

![image](https://github.com/BasavarajAili1/Vehicle-Detection-Counting-Using-OpenCV/assets/112578014/ae1e4747-d2a9-42bf-959b-ad101e94116d)

✔The area below the horizontal line y = 80 is our vehicle detection zone. We will detect any movement that happens in this zone only. You can create your own detection zone if you want to play around with the concept.

## Advantages👌
•	Surveying is easy <br>
•	Maintenance is easy <b>
•	Transport/Logistics Companies may take better usage <b>
•	Traffic Management

# Here we go for a demo 🐱‍🏍
https://github.com/BasavarajAili1/vehicle-detection-and-counting/assets/112578014/41f123a8-9546-459b-b45e-0bee6becb6d2

