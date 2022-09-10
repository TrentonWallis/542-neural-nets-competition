# Classifying gait and terrain of patient based on IMU data from prosthetic limb 

## Project Overview

### Logistics
This repository contains the results of a group project that three undergraduate students ([Nathan Kohen](TODO LINK TO NATHANS GITHUB ACCOUNT), [Trenton Wallis](https://github.com/trentonwallis), and [Caleb Wheeler](https://github.com/cbwheele)) worked on in Spring of 2022. It was a competition project in the Neural Networks class [ECE 542](https://www.engineeringonline.ncsu.edu/course/ece-542-neural-networks/) taught by [Dr. Edgar Lobaton](https://www.linkedin.com/in/lobaton/). The competition nature of the project meant that performance was scaled based on the accuracy of 140 other students in the graduate-level class.  

### Objective
The objective of the project was to create a data filtering process and machine learning model from scratch that could identify the type of terrain a patient was walking over and the gait of the patient based on the inputs from a six-channel IMU. The four classifications were:
- Walking or standing on solid ground
- Walking down stairs
- Walking up stairs
- Walking over grass

### Motivation
Our professor, Dr. Lobaton, is doing exciting research in his lab into advancements robotic prothetic limbs, and one specific area is looking in to is the ways that the movement of these limbs need to change depending on the gait and terrain a patient is walking over. If a machine learning model could be deployed along with an IMU on a prosthetic limb, it could accurately predict the terrain and gait of the patient and adjust the movements of the prosthetic limb to make usage safer and smoother for the patient.

### [Data](./Data) 
We were given real-world data recorded by Dr. Lobaton in his lab that contained the sensor measurements from tests in his lab. We were given data from 28 different session of around 20 minutes in length taken from eight different patients. This data was sampled at 40 Hz, which meant there were 2,400 samples per minute during the sessions. The data inputs were:
- Gyroscope X, Y, and Z axes
- Accelerometer X, Y, and Z axes
They were delivered to us in two csv files per session: one for the measurements and another for the timestamps corresponding to when those 


### Grading Process

### 
