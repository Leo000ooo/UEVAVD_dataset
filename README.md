# UEVAVD_dataset
Description: 
UEVAVD dataset consists of synthetic multi-view aerial images of five vehicle targets (Hatchback, Pickup, Sedan, Sportscar and SUV) under different terrains and occlusion conditions. Using the combination of these observations, one could simulate the process of the UAV’s continuous observation while moving along the trajectory.

Goal:
We release a new dataset, UEVAVD, aiming to promote the research on the UAV’s eye view AOD problem, whose aim is to find out how to better exploit the UAV’s autonomy and maneuverability to overcome difficulties like occlusion in UAV-based object detection.

# Share link
Download using 360 FangCloud
https://v2.fangcloud.com/share/d26b898420a5f8eab1f6453480

Content:
The folder named UEVAVD dataset contains one subfolder and one zip file. The former cover data from 151 scenes, which is stored in order. Each scene corresponds to a subfolder, including the multi-view images and their annoations (bounding boxes), and the images are named under the rule of "UAV's coordinates + target name +scene ID". Each 30 subfolders correspond to a single target. The "00" subfolder is the scene with absolute no occlusion. The zip file named "train_605" consists of crops from the multi-view images concerning five targets with no occlusion. They can be used for training the classifier.

# RAL Paper: UEVAVD: A Dataset for Developing UAV's Eye View Active Object Detection. 
If you find this dataset helpful, please cite our paper whose bibtex is given as follows.

@ARTICLE{10982158,

  author={Jiang, Xinhua and Liu, Tianpeng and Liu, Li and Liu, Zhen and Liu, Yongxiang},
  
  journal={IEEE Robotics and Automation Letters}, 
  
  title={UEVAVD: A Dataset for Developing UAV's Eye View Active Object Detection}, 
  
  year={2025},
  
  volume={10},
  
  number={6},
  
  pages={6272-6279},
  
  keywords={Autonomous aerial vehicles;Object detection;Training;Air to ground communication;Deep reinforcement learning;Technological innovation;Stars;Observability;Information filters;Indoor environment;Active object detection;dataset for active vision;deep reinforcement learning;unmanned aerial vehicle},
  
  doi={10.1109/LRA.2025.3566604}}
