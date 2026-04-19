# License Plate Detection (CV vs YOLO)

## Overview
This project compares **classical computer vision** and **YOLO (deep learning)** for license plate detection using the CCPD dataset.

## Approach
- **Classical CV:** Edge detection, morphology, contour filtering  
- **YOLO:** Trained on bounding boxes converted from CCPD filenames

## Results
YOLO significantly outperforms classical methods:
- Higher detection rate  
- Much better localization (IoU)

## Conclusion
Deep learning (YOLO) provides robust and accurate detection, while classical CV struggles under real-world conditions (blur, rotation, lighting).
