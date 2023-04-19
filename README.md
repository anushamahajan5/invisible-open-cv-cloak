# invisible-open-cv-cloak
OPENCV stands for open source computer vision. It finds its application in many AI models and find its role in self-driven cars and robotics
The use of open cv in this project is to store real-time videos and manipulate the retreived videos

HOW THE PROJECT WORKS?
as soon as the video starts recording, we capture the background preset and it is stored as the initial frame
after that when other frames appear, the cv identifies the colors present in the frame. since we programmed the computer to remove red color, it will find all the elements of red RGB color and remove that
after the removal that part of video/frame will be replaced by the initial reference frame. hence, it creates an invisible effect
