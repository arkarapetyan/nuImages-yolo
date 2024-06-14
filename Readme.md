# Object Detection on nuImages Dataset Using YOLOv8

## Project Description

This project was part of the final project assignment from Advanced ML course in Armenian Code Academy. With this project, 
we trained [YoloV8](https://docs.ultralytics.com) Large model on the [nuImages Dataset](https://nuscenes.org/nuimages) to detect 
objects in urban sceneries for Autonomous Driving Vehicles.

The Model Training was done in Kaggle Notebooks, on 2xT4 GPUs for 16 epochs. Below are the results after the training:

| model/parameters | model/GFLOPs | model/speed_PyTorch(ms) | metrics/precision(B) | metrics/recall(B) | metrics/mAP50(B) | metrics/mAP50-95(B) | fitness  |
|------------------|--------------|-------------------------|----------------------|-------------------|------------------|---------------------|----------|
| 43649115         | 165.506      | 20.171                  | 0.6589971196227412   | 0.4699560568098951| 0.48696434700947755| 0.33002760868653314| 0.3457212825188276 |


## Contributors

Please note that this is a group project. The following individuals have made contributions in this project:

- [Aren Karapetyan](https://github.com/arkarapetyan/)
- [Edgar Harutyunyan](https://github.com/edgarharutyunyan001)

---
## Feed

### 1.0.0 (14.06.2024)
- Refactored Notebooks.
- Replaced CLI Commands with Python Scripts.
- Added Slides.
- Added README.

### 0.9.0 (25.05.2024)
- Initial Commit.
- Added Notebooks for Dataset Creation, Model Training and Prediction.