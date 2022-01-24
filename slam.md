---
layout: default
title: ShanghaiTech Automation and Robotics Datasets
---

## SLAM Datasets

Datasets from the ShanghaiTech Automation and Robotics Center ([STAR Center](https://star-center.shanghaitech.edu.cn/)) for research on Simultaneous Localization And Mapping (SLAM).


<ul id="datasets">
	<li> 
	  <img src="/imgs/mars.jpg"/>
	  <h3><a target="_blank" href="https://robotics.shanghaitech.edu.cn/datasets/MARS-Dataset">MARS Dataset</a></h3>
	  Three indoor datasets with the MARS Mapping Robot.
		<ul>
			<li> Sensors:<br>
				9x RGB camera (5MP, 10Hz)<br>
				2x 32beam Velodyne LiDAR<br>
			1x IMU</li>
			<li> Duration: 704sec</li>
			<li> Distance: 177m</li>
			<li> Size: 120GB</li>
			<li> Scene: Indoor Lab</li> 
			<li> Format: ROS 1 Bag</li> 
			<li> Ground truth: Tracking System, ground truth map</li>
			<li> Paper: Chen et al. <a href="https://doi.org/10.1016/j.robot.2020.103559" target="_blank">Advanced mapping robot and high-resolution dataset</a>, Robotics and Autonomous Systems, Elsevier, 2020</li>
		</ul>
	</li>	<li> 
	  <img src="/imgs/vins-rgbd.jpg"/>
	  <h3><a target="_blank" href="https://robotics.shanghaitech.edu.cn/datasets/VINS-RGBD">VINS-RGBD</a></h3>
	  Three datasets collected with an Intel RealSense camera (Handheld, wheeled & tracked robot).
		<ul>
			<li> Sensor: RGBD: IntelRealsense D435i with IMU</li>
			<li> Duration: 585 sec</li>   
			<li> Distance: 50 m</li> 
			<li> Size: 16GB</li>
			<li> Scene: Indoor Lab</li> 
			<li> Format: ROS 1 Bag</li> 
			<li> Ground truth: Tracking System</li>
			<li> Paper: Shan et al. <a href="https://doi.org/10.3390/s19102251" target="_blank">RGBD-Inertial Trajectory Estimation and Mapping for Ground Robots</a>, Sensors, MDPI, 2019</li>
		</ul>
	</li>
</ul>



