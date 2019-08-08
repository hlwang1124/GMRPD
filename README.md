# Wheelchair Dataset

This is an RGB-D dataset of drivable area and road anomaly segmentation for robotic wheelchairs. 

Now there are a total of 3036 RGB-D images with hand-labeled segmentation ground truth, which cover 30 common scenes where robotic wheelchairs usually work (e.g., sidewalks and squares) and 18 different kinds of road anomalies that robotic wheelchairs may encounter in real environments. The whole dataset that contains 3896 RGB-D images will be uploaded soon.

The whole dataset is seperated into three small datasets, each of which contains 10 scenes. The link of the dataset is shown as follows,

https://drive.google.com/file/d/1hvq_0ozBsYDD9Vd0_fl9QLHPje7xap0h/view?usp=sharing
https://drive.google.com/file/d/1Pwuxf0ML3i3tU8uGnemty4K4uN7v0o4i/view?usp=sharing
https://drive.google.com/file/d/1eW904LKnse4ksKwyYET-WqROOY1nrJm1/view?usp=sharing

RGB images, normalized depth images, original depth images and segmentation labels are stored in "rgb", "depth_u8", "depth_u16" and "label" folder, respectively. The resolution of the images is 1280 x 720 pixels. 

Since there exist invalid pixels on both sides of the depth images collected by RealSense D415 Camera, we recommend cropping the images before use.

Please use this bibtex if you want to cite this repository in your publications:
```
@ARTICLE{wang2019self, 
author={Hengli Wang and Yuxiang Sun and Ming Liu}, 
journal={{IEEE Robotics and Automation Letters}}, 
title={{Self-Supervised Drivable Area and Road Anomaly Segmentation using RGB-D Data for Robotic Wheelchairs}}, 
year={2019}, 
volume={}, 
number={}, 
pages={1-1}, 
doi={10.1109/LRA.2019.2932874}, 
ISSN={2377-3766}, 
month={},}
```
