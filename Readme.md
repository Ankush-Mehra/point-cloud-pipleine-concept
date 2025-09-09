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
Bounding boxes are generated around each cluster.  
<img src="images/point-cloud-pipeline.gif" width="600" />


---

## ⚙️ Hardware Setup  
LiDAR hardware used : **Velodyne HDL-64E**  
![LiDAR Hardware](images/lidar_velodyne_kitti.jpg)

---

