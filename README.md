

## Shop names detection 

## Table of Contents
- [Project_Description](#project-description)
- [ProjectStructure](#project-structure)
- [Prerequisites](#prerequisites)
- [limitations](#limitations)

## Project Descriptions

- Project is used to detect the shop names by using yolo detection model
- here it is detecting shop names from the video



## Project Structure
```
.
├──dataset                   # folder containing dataset
    ├── train                             # images used for training
    ├── test                              # images used for testing 
    ├── val                               # images used for validation
├── detect                   # folder contains training with different models
├── models                   # models used for training
├── video_frame              # video used for dataset       
├── README.md                # README file

```
## Prerequisites

-visual studios 2022+  <br>
-pytorch <br>
-open cv version 4.70 + <br>

## Limitations
- trained on less dataset need to train on more dataset with good quality of data for accurate result