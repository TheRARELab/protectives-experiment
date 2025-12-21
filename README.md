# protectives-experiment
This project is for the Pepper robot in experiment investigating protectives to mitigate robot abuse

## System requirements
+ Versions the software has been tested on:
  - Choregraphe 2.5.10.7
  - Windows 11
+ Robot platform:
  - [Pepper](https://aldebaran.com/pepper/) by Aldebaran Robotics

## Installation guide
+ Download and install Choreograph 2.5 by following the [official installation guide](http://doc.aldebaran.com/2-5/software/choregraphe/installing.html)
  - Licence key: 654e-4564-153c-6518-2f44-7562-206e-4c60-5f47-5f45

## Instructions for use
+ Open the project by clicking on protectives-experiment.pml.
+ Turn off Autonomous Life of the robot by clicking on the heart icon on the top right.
+ Wake Pepper up by clicking on the 'Wake Up' on top right corner.
+ Wait for Pepper to wake up and stretch.
+ For Baseline, Armor, and  Headgear conditions, run the behavior.xar file in the 'Baseline-Armor-Headgear' folder:
  - Pepper will start looking at Worker 1.
  - Wait for Worker 1 to finish their first sentence or similar to the wrench hand-over request.
  - After that, double click on the 'go' button on 'Dialogue_1' box.
  - Wait for Worker 1 to finish their second sentence from the script or similar to clarifying the position of the wrench.
  - After that, double click on the 'go' button on 'Dialogue_2' box. Pepper will say her sentence, scan the table, and hand over the wrench to Worker 1.
  - Wait for Worker 1 to finish their fourth sentence from the script or similar to the saw hand-over request.
  - After that, double click on the 'go' button on 'Dialogue_3' box.
  - Wait for Worker 1 to finish their fifth sentence from the script or similar to clarifying the position of the saw.
  - After that, double click on the 'go' button on 'Dialogue_4' box. Pepper will say her sentence, scan the table, and hand over the saw to Worker 1.

+ For Shield condition, run the behavior.xar file in the 'Shield' folder:
  - Pepper will wield the shield close to her body and start looking at Worker 1.
  - Wait for Worker 1 to finish their first sentence or similar to the wrench hand-over request.
  - After that, double click on the 'go' button on 'Dialogue_1' box.
  - Wait for Worker 1 to finish their second sentence from the script or similar to clarifying the position of the wrench.
  - After that, double click on the 'go' button on 'Dialogue_2' box. Pepper will say her sentence, scan the table, and hand over the wrench to Worker 1.
  - Wait for Worker 1 to finish their fourth sentence from the script or similar to the saw hand-over request.
  - After that, double click on the 'go' button on 'Dialogue_3' box.
  - Wait for Worker 1 to finish their fifth sentence from the script or similar to clarifying the position of the saw.
  - After that, double click on the 'go' button on 'Dialogue_4' box. Pepper will say her sentence, scan the table, and hand over the saw to Worker 1. 

+ For wielding the shield, run behavior.car file in HoldShield folder:
  - Pepper will wield the shield using left arm. 
