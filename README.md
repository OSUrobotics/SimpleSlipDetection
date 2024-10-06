# SimpleSlipDetection
This repository contains the data used in the manuscript "Slip detection with simple sensors and simple hands"

The data is organized at the top level by grasped object, then by trial. Each trial folder contains kinematic information in the form of object and link poses and object and link velocities. Each list entry in each .csv file corresponds to a particular 1/8th second frame in the data. Data with the same index, or position in this list, is from the same frame, which can be used to associate data across files. The timestamps, which represent the end time of the frame, are in their own file.

The IMU data and machine learning features and labels are also available within each trial folder. The machine learning labels are presented as a list of four boolean values, each of which corresponds to one of the thresholds from the manuscript. The first index represents 0.25 cm/s, the second 0.5 cm/s, the third 0.75 cm/s, and the fourth 1.0 cm/s.

The original output from the Optitrack is also available in its own folder. There is one .csv file per trial of Optitrack data.

Finally, the folders for each grasped object are additionally available as .zip files for easier download.
