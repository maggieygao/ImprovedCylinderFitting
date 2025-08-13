Cylinder Fitting & Sectional Analysis for Rebar Point Clouds
This repository provides Python scripts for automatic clustering, cylinder fitting, and sectional analysis of rebar elements from 3D point cloud data.
It supports Open3D-based visualization, DBSCAN clustering, PCA-based axis estimation, least-squares refinement, and statistical analysis of rebar dimensions.

Features
Load and visualize .ply or .pcd point cloud files
Statistical outlier removal
Automatic point density analysis and DBSCAN parameter suggestion
Clustering of rebar point sets
PCA-based axis estimation
Least-squares cylinder fitting refinement
Sectional diameter analysis
Multi-view 3D visualizations (Open3D & Matplotlib)
Computation time and cost estimation

Requirements
Tested on Python 3.9+.
Install dependencies via:
open3d
numpy
matplotlib
scikit-learn
scipy

Terminal output with clustering stats, cylinder dimensions, and computation cost
Open3D interactive 3D windows for:
Original and cleaned point clouds
Clustered rebar elements
Fitted cylinder wireframes & surfaces

Matplotlib plots for:
Sectional diameter variations
Length, RMSE, and processing time
Dimension distributions

