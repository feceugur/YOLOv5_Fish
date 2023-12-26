# YOLOv5_Fish
FishDetectionAndTracking with YOLOv5

In my first experience with YOLO, I will try to train with underwater images to detect and track fish. Stay tuned to see my progress :D 
## 1. Model

## 2. About Dataset

The F4K Detection and Tracking dataset includes 17 videos (10 minutes long each) with a resolution of 320x240 and a 24-bit color depth at a frame rate of 5 fps. These videos were selected by considering the presence of specific features that depict both standard and non-standard conditions (e.g. dynamic background, illumination variations, high water turbidity, very low contrast, crowded scenes, and camouflage) for the observed environment. For each video, the ground truth is available only for specific key frames identified as those containing the highest number of objects of interest for the current video. The recorded ground truth is available in XML format where keyframes are listed at the beginning of the file together with the video class (e.g. "Blurred", "DynamicBkg", "Crowded", etc.). For each frame, a list of objects is available with trackingId, detectionID, and objectType. Finally, contour information is recorded as sequences of (x,y) coordinate pairs for each object in the current frame.

#### Download dataset
Link to dataset files: https://bit.ly/f4k-detection-tracking

#### Citation

I. Kavasidis, S. Palazzo, R. Di Salvo, D. Giordano, C. Spampinato, An innovative web-based collaborative platform for video annotation, Multimedia Tools and Applications, vol. 70, pp. 413-432, 2013.

I. Kavasidis, S. Palazzo, R. Di Salvo, D. Giordano, C. Spampinato, A semi-automatic tool for detection and tracking ground truth generation in videos, Proceedings of the 1st International Workshop on Visual Interfaces for Ground Truth Collection in Computer Vision Applications, pp. 6:1-6:5, 2012.


