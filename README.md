## News!
* **After the review is complete, we plan to release the new version.**
* **Finally, our paper is accepted in IEEE Sensor Letter!!**
	* We will provide the final citation once the paper is published.


## Download
* The dataset is provided on-demand, by following a [request link](https://forms.gle/v6ehRxSDsVq6xVa48). Please fill out a simple form to us, and you will get a automated response mail containing full download links.



## DiTer
* **DiTer: Diverse Terrain and Multi-Modal Dataset for Field Robot Navigation in Outdoor Environments**
	* Accepted in IEEE Sensors Letter 2024

* **Sensor Configuration** 
	* We configure the legged robot with various sensors offered in multi-session datasets.
	<p align="center"><img src=fig/sensor_setup.png /></p>

## Example Sequence in HILL01-A
* Our perceptual sensor data.
	<p align="center"><img src=fig/sensor.gif /></p>

## Calibration
* Using the [camera-lidar calibration toolbox](https://github.com/acfr/cam_lidar_calibration), we calibrate camera-LiDAR and thermal-LiDAR.
* For calibrating thermal camera and LiDAR, we proceed by inverting the thermal image due to the opposite nature of heat and color characteristics.
<p align="center"><img src=fig/calibration.png /></p>

## Trajectory
* Utilizing the [FAST-LIO](https://github.com/hku-mars/FAST_LIO), we provide a reference trajectory. 
<p align="center"><img src=fig/trajectory.png /></p>

## Map
* We construct a global map by accumulating pointclouds through the reference trajectory.
<p align="center"><img src=fig/map.png /></p>

## Cite DiTer
<pre>
<code>
@article{jeongditer,
  title={DiTer: Diverse Terrain and Multi-Modal Dataset for Field Robot Navigation in Outdoor Environments},
  author={Jeong, Seokhwan and Kim, Hogyun and Cho, Younggun}
}
</code>
</pre>  

## Contact
* **Seokhwan Jeong (eric5709@inha.edu)**
* **Hogyun Kim (hg.kim@inha.edu)**

## Supplementary
* **[Google Sites](https://sites.google.com/inha.edu/diter/)**
* **[Youtube](https://www.youtube.com/watch?v=i-2FwYKT5ss)**

