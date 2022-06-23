# counting-people-using-python
Crowd counting is a process of counting number of people in videos or images .This process hasvarious applications related to our day to day life such as urban planning, health care, disaster management, public safety management, and defense. Thus new researches are going on in this field. The crowd techniques are broadly classified as supervised learning based and unsupervised learning based techniques. Some of traditional and convolutional neural network crowd counting techniques are there. Crowd counting techniques are facing various limitations such as occlusion, distortion in scale and perspective, non uniform distribution. As the crowd density increases, calculation complexity also increases. Most of the crowd counting methods involves density estimation. Density estimation gives an idea about the spatial distribution of people along with the count.Here in this project we are going to find the number of humans present in the live video. Number of humans can be calculated using face detection using image processing. For each detected human face we display a square box along with the count on the top of the box.For the detection of human face here we used python language in the spyder IDE and libraries like OpenCV,numpy and dlib.
This project is a better method which consumes less time with less complexity to count the number of human faces in the live stream.
Step-1:
The webcam connected to the system or the camera of the system activates and starts capturing the video.
 Step-2:
As soon as the camera starts it starts to find the coordinates of multiple faces present in the video frame.
 Step-3:
After detecting the face coordinates it starts capturing the human faces present in the video frame.
 Step-4:
As the number of faces are captured in the frame,the count keeps increasing.
 Step-5:
 Each face will be denoted by a numeric number and the highest number is the number of faces in the video.
