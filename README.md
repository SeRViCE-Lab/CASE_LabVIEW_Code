## A Real-Time Soft Robotic Patient Positioning System for Maskless Head-and-Neck Cancer Radiotherapy: An Initial 
Investigation

**Authors: Olalekan Ogunmolu, Xuejun Gu, Steve Jiang, Nicholas Gans**

###Maintainer: Olalekan P. Ogunmolu
This code is the implementation of my [paper](http://arxiv.org/pdf/1506.04787v1) which will be presented at the 2015 IEEE Conference on Automation Science and Engineering in Gothenburg, Sweden.

###Abstract
We present an initial examination of a novel approach to accurately position a patient during head and neck intensity modulated radiotherapy (IMRT). Position-based visual-servoing of a radio-transparent soft robot is used to control the flexion/extension cranial motion of a manikin head. A Kinect RGB-D camera is used to measure head position and the error between the sensed and desired position is used to control a pneumatic system which regulates pressure within 
an inflatable air bladder (IAB). Results show that the system is capable of controlling head motion to within 2mm with respect to a reference trajectory. This establishes proof-of-concept that using multiple IABs and actuators can improve cancer treatment.

###Notes
We basically develop a second-order linear process model following a classical system identification approach and 
develop a classical cascade PID/PD controller for the model we developed.
The head position of the manikin head was measured with an RGB-D camera which gave positions of the head movement 
upon actuation by a soft-robot in real-time and at 30Hz. To implement thos code, you would need a 
**National Instruments Reconfigurable Input/Output** system such as **myRIO** or **cRIO**.

Please read the paper for more details. 

###Questions
If you have any problem implementing the code, please raise an [issue](https://github.com/lakehanne/CASE_LabVIEW_Code/issues). 
I will generally respond within a 24-hour period.
