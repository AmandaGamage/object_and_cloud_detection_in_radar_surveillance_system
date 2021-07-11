# object_and_cloud_detection_in_radar_surveillance_system

Cloud detection is a vital component in civilian radars.Rain clouds can have a down- craft which can be dangerous as they can generate an electrical charge. Therefore, they must be avoided by pilots.

The three files (Test_case1.csv, Test_case2.csv, and Test_case3.csv) contain the input for first three test cases. Each test case contains 18000 samples of the output present after demodulation. These samples are taken at a very high sampling rate (1080 KHz) to give you the essence of a continuous signal so you are expected to down-sample the signal to fit into 30 range slots.Your task is to use this demodulated signal to identify clouds and targets present using threshold detection and post detection integration. For threshold detection use a window size of 21 on the original samples( samples taken @ 1080KHz) to determine the average noise voltage for a particular range slot. A guard band of 4 would be appropriate in this case. Output of a few example cases are given in the proceeding sections to illustrate the procedure. In the presence of clouds identify the rough contour depicting the cloud. In the presence of a target indicate the range and the azimuth angle assuming the initial azimuth angle is zero.

Radar Description:
Pulse Repetition Frequency = 1800Hz 
Horizontal Beam Width = 2 o 
Number of Revs per minute = 12
σn = 1
