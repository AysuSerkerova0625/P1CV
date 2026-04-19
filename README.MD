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


## Dataset

The dataset used in this project is available on Kaggle:

- Train Data
https://www.kaggle.com/datasets/aysuserkerova/traindata

- Test Data
https://www.kaggle.com/datasets/aysuserkerova/testdata

Due to its large size, it is not included in this repository.
