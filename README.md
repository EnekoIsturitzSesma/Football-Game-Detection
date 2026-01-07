# Football Game Detection

This project implements a computer vision system based on YOLO (You Only Look Once) for the detection and classification of key elements in football matches. The main objective is to identify and locate players, referees, goalkeepers, and the ball in images or video sequences. In order to determine if there's an offside situation or not.

## Description

The system uses deep learning models to process images of football fields and detect the following classes:

*   **Ball**
*   **Goalkeeper**
*   **Player**
*   **Referee**

The project has been developed using the `ultralytics` library and is trained on a custom dataset.

Then a 2D projection of the 3D space is created using the detected objects.
And finally, the offside situation is determined based on the 2D projection. 
## Requirements

To run this project, Python 3.8 or higher is required, along with the following main libraries:

*   `ultralytics`
*   `torch` (with CUDA support recommended for training)

Dependency installation:

```bash
pip install ultralytics torch
```
