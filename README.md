# Ground Mobile Robot Perception Dataset

This is an RGB-D dataset of drivable area and road anomaly segmentation for ground mobile robots (e.g., sweeping robots and robotic wheelchairs).

Now there are a total of 3036 RGB-D images with hand-labeled segmentation ground truth, which cover 30 common scenes where ground mobile robots usually work (e.g., sidewalks and squares) and 18 different kinds of road anomalies that ground mobile robots may encounter in real environments. The whole dataset that contains 3896 RGB-D images will be uploaded soon.

The whole dataset is seperated into three small datasets, each of which contains 10 scenes. The link of the dataset is shown as follows,

https://drive.google.com/file/d/1z5QVvhv6LaG7HHZ2OEVNE9aepIHEMjIO/view?usp=sharing

https://drive.google.com/file/d/1qU-DfGeSOP5atixT6oe9oM_OM_gQjHlu/view?usp=sharing

https://drive.google.com/file/d/1udLqjgH48yaAcT30Op-pweHnMC3_vuVM/view?usp=sharing

RGB images, normalized depth images, original depth images and segmentation labels are stored in "rgb", "depth_u8", "depth_u16" and "label" folder, respectively. The resolution of the images is 1280 x 720 pixels. 

Since there exist invalid pixels on both sides of the depth images collected by RealSense D415 Camera, we recommend cropping the images before use.

Please use this bibtex if you want to cite this repository in your publications:
```
@article{wang2020dynamic,
  title={Dynamic Fusion Module Evolves Drivable Area and Road Anomaly Detection: A Benchmark and Algorithms},
  author={Wang, Hengli and Fan, Rui and Sun, Yuxiang and Liu, Ming},
  year={2020},
  note={under review}
}
```
```
@article{wang2019self, 
  author={Wang, Hengli and Sun, Yuxiang and Liu, Ming},
  journal={IEEE Robotics and Automation Letters}, 
  title={Self-Supervised Drivable Area and Road Anomaly Segmentation Using RGB-D Data For Robotic Wheelchairs}, 
  year={2019}, 
  volume={4}, 
  number={4}, 
  pages={4386-4393}, 
  doi={10.1109/LRA.2019.2932874}, 
  ISSN={2377-3766}, 
  month={Oct}
}
```
