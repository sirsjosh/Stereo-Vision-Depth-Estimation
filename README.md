# Stereo Vision Depth Estimation

<img src='' />

This repository contains a project focused on **stereo vision depth estimation** using Python and computer vision techniques. The goal of the project is to reconstruct the 3D structure of a scene from two stereo images, enabling depth perception through disparity map generation, and ultimately creating a 3D point cloud representation of the scene.

## Project Overview

Stereo vision is a technique used in computer vision to estimate the depth of objects in a scene by comparing the disparities between two images taken from slightly different viewpoints. By computing the disparity between corresponding points in the left and right images, we can infer the depth of objects in the scene. This project demonstrates how to:

- Load stereo image pairs
- Calculate the disparity map using algorithms like **Stereo BM** and **Stereo SGBM**
- Use camera calibration parameters to compute depth maps
- Generate a 3D point cloud from stereo images for visualization
- Visualize depth estimation results

## Key Concepts

- **Disparity Map**: A disparity map is the visual representation of the difference between the corresponding pixels in the left and right images of a stereo pair. The greater the disparity, the closer the object in the scene.
  
- **Depth Map**: A depth map is generated from the disparity map, representing the relative distances of objects from the camera.

- **3D Point Cloud**: A 3D point cloud is a collection of points in three-dimensional space that represent the 3D shape of objects in a scene.

## Installation

To run this project, you’ll need Python 3.x along with several dependencies. It is recommended to use a virtual environment to manage the dependencies.

### 1. Clone the repository:

```bash
git clone https://github.com/sirsjosh/Stereo-Vision-Depth-Estimation.git
cd Stereo-Vision-Depth-Estimation
