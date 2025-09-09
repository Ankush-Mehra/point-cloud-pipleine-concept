# Point Cloud Processing Pipeline

This project demonstrates a LiDAR point cloud processing pipeline with visualization, filtering, ground separation, clustering, and bounding box generation.  
Everything shown here is unoptimized and for **demonstration purposes only**.  

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
The complete processed point cloud with bounding boxes.  
<video src="images/Output.avi" controls width="600"></video>

---

## ⚙️ Hardware Setup  

This project was developed and tested using the following LiDAR hardware:  
![LiDAR Hardware](images/lidar_velodyne_kitti.jpg)

---

## 📂 Project Structure (for reference)



```python

```
