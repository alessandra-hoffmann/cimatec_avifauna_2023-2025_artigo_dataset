# Monocular Deep Learning Pipeline for 3D Bird Collision Risk Assessment on Power Transmission Lines

This repository is the code for a scientific paper currently under review for Brazilian Archives of Biology and Technology.

## Abstract

This work aims to assess the risk of colission of flying birds with transmission line. This is achieved using a 3D reconstruction based on monocular depth estimation.

## Requirements

The provided code can be executed on a Jupyter environment running python.

It is necessary to git clone the Deep-Anything-V2 on the working directory: https://github.com/DepthAnything/Depth-Anything-V2.

Other requirements are given in requirements.txt file.

## Structure and important files: 

- **dataset/**: Folder that contains the annotated dataset of flying birds
- **load_video.ipynb**: Read video files with detected birds and apply the depth anything V2 to frames. Save the results as CSVs.
- **distance_regression.ipynb:** Read the csvs from load_video and perform:
  -  Different regressions to find the best regression model;
  -  Filtering to the time series data
  -  Risk estimation
- Study scripts folder: Folders with preliminary code. 

## Contact

pedro.medina@fbter.org.br

marco.rueda@fieb.org.br

benito.torre@fieb.org.br

tacito.silva@fieb.org.br

Made by Senai Cimatec in partnership with State Grid Holding S.A

