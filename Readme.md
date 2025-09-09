# Point Cloud Processing Pipeline Concept Only

This project demonstrates a LiDAR point cloud processing pipeline with visualization, filtering, ground separation, clustering, and bounding box generation.  

---

## 🖼️ Pipeline Overview

### 1. Visualization with Reflectance  
Reflectance values are mapped to the **red channel** for visual clarity.  
![Visualization](images/Reflectance.png)

### 2. Filtering by Reflectivity Threshold  
Low-reflectivity points are filtered out.  
![Filtering](images/Threshold_Reflectance.png)

### 3. Ground Separation (RANSAC)  
Ground points are removed using **RANSAC plane fitting**.  
![Ground Separation](images/Ransac_Ground_Separation.png)

### 4. Clustering with DBSCAN  
Objects are clustered using **DBSCAN**.  
![Clustering](images/Dbscan_Clusters.png)

### 5. Axis-Aligned Bounding Boxes  
Bounding boxes are generated around each cluster.  
![Bounding Boxes](images/Bounding_Boxes_AA.png)

### 6. Final Output  
The complete processed point cloud with bounding boxes.  <br>
[![Watch the point cloud processing pipeline demo video](https://img.youtube.com/vi/NG4hXilxNBk/0.jpg)](https://youtu.be/NG4hXilxNBk)

---

## ⚙️ Hardware Setup  

This project was developed and tested using the following LiDAR hardware: **Velodyne HDL-64E** 
![LiDAR Hardware](images/lidar_velodyne_kitti.jpg)

---

## 📂 Project Structure (for reference)



```python

```
