Acoustic-and-Vibration-Fault-Detection-in-Rotating-Machines-Test-Results
========================================================================

This repository contains MSc in Sustainable Energy Systems Dissertation Thesis Test Results


Note:
Acoustic Emissions Results:

* Some of the files contain a distinctive noise at the beginning and at the end. Such noise is
  introduced to allowed synchronization between the smartphone recording and high-fidelity microphone recording.
  
* Some of the files contain sections with background noise. Play the file to verify that selected timeframe is free from background noise.


* Naming Convention:

	
	MotorID_TestType_SubTestType_SyncCode_Distance_MicConfiguration_Orientation_InverterFrequency.wav
	
	
	SyncCode is an incremental integer value used to identify the smartphone and the high fidelity microphone simultaneous recordings.
	Therefore, files with the same SyncCode where recorded at the same time. MicConfiguration is only included in the high fidelity microphone recordings tag when the high fidelity microphone configuration is omnidirectional. Orientation is only included in tag when the microphones are not facing motor front side (0°).







Vibration Results:
* Vibration results are in CSV format. The coding is as follows:

Start_of_File = 999
End_of_File = 111

Start_of_File,Start_of_File,Start_of_File,Start_of_File,Start_of_File,Start_of_File,Start_of_File;X_axis_averaged,Y_axis_averaged,Z_axis_averaged,X_axis,Y_axis,Z_axis,TimeStamp;End_of_File,End_of_File,End_of_File,End_of_File,End_of_File,End_of_File,End_of_File;
  
  
* Naming Convention:
	
	MotorID_TestType_SubTestType_SmartphoneOrientation_DeviceLocation_InverterSupplyFrequency_NoCase.dat


	DeviceLocation is only included in tag when the smartphone location is different than induction motor power box. NoCase is only included in tag when the smartphone is not using protection case.
  