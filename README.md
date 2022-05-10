# huSync - A computational approach and system for computing dyadic synchronization in small groups

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
Use case for the paper submission in IEEE Access:
_Video sequences of a professional musical ensemble_

This repository contains the code that was developed in order to compute Dyadic Synchronization between participants in small groups.
We test our system on video sequences of co-performers in a small group of musicians.
	
## Technologies
Project is created with:
* Lorem version: 12.3
* Ipsum version: 2.33
* Ament library version: 999
	
## Setup
To run this project, install it locally using npm:




The repo contains two files:
  1. Module_DataExtraction: This file contains the code that extracts the data for each performers by isolating them individually. It stores the output as a .csv file
  2. Module_DyadicSynchronization: This file contains the code that extracts the data from the .csv file processed by the first file (Module_DataExtraction), and provides the Dyadic Synchronization between all possible pairs in a small group, and in this case the musical ensemble.


Both the files have been shared as a jupyter notebook since this should make it easier to execute the code with more control.
The added control helps perform experiments carefully, particularly since the data from pose estimation algorithms can be noisy and sometimes requires manual intervention.

##### Code maintained by
Sanket Rajeev Sabharwal (sabharwal@edu.unige.it)

##### Note for researchers:

