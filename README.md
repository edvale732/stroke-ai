## StrokeAI

### A computer vision program to analyse rowing strokes.

### Implemented Features

- Pose Estimation for Single Frame
- Pose Estimation for Video
- Key Joint Angle Extraction
    - knee
    - hip
    - elbow
    - shoulder
    - ankle
    - trunk lean


### Images

Frame from a video showing pose estimation and key joint angle extraction

![Frame with Pose Estimation and Key Joint Angle Extraction](image.png)


### Models

- Pose Estimation 
        - Using MediaPipe Pose Landmarker from Google ([Link](https://developers.google.com/edge/mediapipe/solutions/vision/pose_landmarker/index?_gl=1*z8jxl0*_up*MQ..*_ga*NDE0OTUwMzcwLjE3OTA4NzQyMzU.*_ga_SM8HXJ53K2*czE3OTA4NzQyMzQkbzEkZzAkdDE3OTA4NzQyNDckajQ3JGwwJGgw#models))



### Planned Features

- Stroke Detection
    - Detect Full Stroke, Catch, Drive, Finish, Recovery

- Sequence Analysis
    - Hips opening early
    - Not connecting with legs
    - Arms coming in early