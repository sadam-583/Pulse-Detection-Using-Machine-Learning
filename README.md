# Pulse-Detection-Using-Machine-Learning


                                                       Our Project main aim is to determine the heart rate of a person with out getting into contact to him. So we use a face capturing technique by considering points on forehead region to determine the heart rate. So we collaborated all our files and the user can simply run the project by adding all the collaborated files into the device. And by clicking the “get_pulserate.py” folder the user will be automatically be driven to our project. 

**********************************************************************************

The following are the necessary actions to be taken to run our project :
⦁	 When run, a window will open showing a stream from your computer's webcam
⦁	When a forehead location has been isolated, the user should press "S" on their keyboard to lock this location, and remain as still as possible (the camera stream window    must have focus for the click to register). This freezes the acquisition location in place. This lock can be released by pressing "S" again.
⦁	To view a stream of the measured data as it is gathered, press "D". To hide this display, press "D" again.
⦁	The data display shows three data traces, from top to bottom:
⦁	raw optical intensity
⦁	extracted heartbeat signal
⦁	Power spectral density, with local maxima indicating the heartrate (in beats per minute).
⦁	With consistent lighting and minimal head motion, a stable heartbeat should be isolated in about 15 to 20 seconds. A count-down is shown in the image frame.
⦁	If a large spike in optical intensity is measured in the data (due to motion noise, sudden change in lighting, etc) the data collection process is reset and started over. The sensitivity of this feature can be tweaked by changing data spike limit on line 31 of ⦁	get_pulse⦁	rate⦁	.py. Other mutable parameters of the analysis can be changed here as well.

These are the basic instructions to be followed to run our project.


********************************************************************

Requirements:
Python v2.7 or v3.5+)
OpenCV v2+
Numpy, Scipy
Visual Studio or Pycharm

***************************************************************************
