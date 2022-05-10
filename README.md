# huSync - A computational approach and system for computing dyadic synchronization in small groups
## Use case for the paper submission in IEEE Access: Video sequences of a professional musical ensemble

This repository contains the code that was developed in order to compute Dyadic Synchronization between participants in small groups.
We test our system on video sequences of co-performers in a small group of musicians.

The repo contains two files:
  1. Module_DataExtraction: This file contains the code that extracts the data for each performers by isolating them individually. It stores the output as a .csv file
  2. Module_DyadicSynchronization: This file contains the code that extracts the data from the .csv file processed by the first file (Module_DataExtraction), and provides the Dyadic Synchronization between all possible pairs in a small group, and in this case the musical ensemble.


Both the files have been shared as a jupyter notebook since this should make it easier to execute the code with more control.
The added control helps perform experiments carefully, particularly since the data from pose estimation algorithms can be noisy and sometimes requires manual intervention.

##### Author

Sanket Rajeev Sabharwal
UniGe, Casa Paganini
4709433
