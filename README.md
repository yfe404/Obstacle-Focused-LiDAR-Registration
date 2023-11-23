# Obstacle-Focused-LiDAR-Registration

## Overview
This Python-based project focuses on the registration of LiDAR point clouds, with a specific emphasis on accurately aligning obstacles. Utilizing Open3D, the project applies a novel approach that involves segmenting the road using RANSAC and then performing registration on the outliers of this segmentation.

## Objective
The aim is to develop a method that ensures precise alignment of both obstacles and roads in point cloud data, enhancing the accuracy and usability of LiDAR data in various applications.

## Methodology
1. **Data Collection**: Acquire two sets of point clouds from LiDAR at different time intervals.
2. **Preprocessing**: Prepare the point clouds for segmentation and registration.
3. **Road Segmentation**: Implement RANSAC to segment out the road surfaces within the point clouds.
4. **Focus on Outliers**: Shift the registration focus to the outliers of the segmented road, which primarily include obstacles.
5. **Registration Process**: Perform the point cloud registration on these outliers.
6. **Applying Transformation**: Extend the transformation obtained from registration to the entire point clouds, ensuring both roads and obstacles are accurately aligned.
7. **Post-Processing & Validation**: Finalize the registration process and validate the alignment accuracy.

## Technologies
- **Python**: Primary programming language.
- **Open3D**: Used for 3D point cloud processing and registration.

## Setup and Installation
(Instructions for setting up and installing the project, including environment setup and library dependencies.)

## Usage
(Detailed guide on how to use the project, including script execution, data input formats, and command-line options.)
