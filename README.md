# SLD_Seminar
Sign Language Detection using LSTM Deep  Learning Model (Action Recognition with Python )
 This project was created intending to use 
computer vision to be able to recognize the Sign Language in 
real time with high accuracy. The reason for such a project is 
to help diminish the gap between those who can hear well and 
those hard of hearing or even deaf. This can be overcome by 
creating a dataset of images that correspond to the alphabets, 
digits or signs applied to deep neural networks. These images 
are labeled according to the letter being signed. They are 
processed through a neural network using transfer learning to 
help the machine “learn” what is being signed after already 
having been taught on larger datasets of many more images 
and classifications.

### Overall Design
In this sign language recognition project, we create a 
sign detector that detects bespoke signs and can be easily 
extended to include a wide range of additional signs and 
hand motions, including the alphabet and numerals.The 
OpenCV, Mediapipe, Tensorflow, and Keras Python 
modules were used to create this project. The OpenCV feed 
examines the frames of live video from a camera to detect 
the action of a person who is being displayed at that moment 
in time. To extract keypoints from our hands, torso, and 
face, the video frames are processed with Media Pipe 
Holistic. The relevant points will then be passed to the 
prediction algorithm, which will begin the prediction. The 
technology then anticipates the hand sign that is being made 
in real time. The expected sign will also be displayed.
### Prerequisites
The prerequisites software & libraries for the sign language 
project are:
• Python (3.10.4)
• IDE (Jupyter)
• Mediapipe (version 0.8.10)
• Numpy (version 1.22.4)
• cv2 (openCV) (version 4.5.5.64)
• Keras (version 2.9.0)
• Tensorflow (as keras uses tensorflow in backend 
and for image preprocessing) (version 2.9.1)
