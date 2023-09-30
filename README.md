# SignalScan
The role of the this system is to detect and recognize road signs in  real-time. This system will alert the driver by making them aware of the signboards before  they pass by.
The input to the system is a video frame which is fed to the YOLO model for the detection 
and recognition of the traffic symbol. YOLO is a one-stage detector based on CNN 
algorithm which utilizes a single neural network to predict both the bounding boxes and 
the class probabilities directly from the input images in one evaluation. Using class 
probabilities and bounding boxes the type and location of traffic sign is decided and finally, 
by using the audio output the driver will be altered regarding the traffic sign.
