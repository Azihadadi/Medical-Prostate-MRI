# Prostate MRI Analysis Tool

## Overview
This repository contains a management and post-processing tool for prostate MRI analysis. The tool is designed to facilitate various operations related to DICOM format manipulation and includes a user-friendly GUI developed in MATLAB.

## Objectives
- Present the functionalities of the tool for prostate MRI analysis.
- Detail the usage procedure for effective operation.
- Provide a database of DICOM images for testing and demonstration.

## Features
- **DICOM Manipulation**: Extract patient information, anonymize data, and convert DICOM files to JPG and vice versa.
- **Prostate Zone Segmentation**: Utilize the Active Contour Model (Snakes) for prostate zone segmentation.
- **Surface and Volume Calculation**: Calculate the surface area and volume of each segmented zone.
- **3D Visualization**: Display segmentation results in a 3D representation.

## Requirements
To run the application, you will need:
- MATLAB (with Image Processing Toolbox)
- A compatible operating system

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Azihadadi/Medical-Prostate-MRI
