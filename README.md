# Airplanes-Detection---Computer-vision
This project focuses on merging datasets for a computer vision task using the YOLOv8 model. It involves setting up the environment, downloading datasets via the Roboflow API, merging them, renaming class labels for consistency, and visualizing samples to ensure data integrity. Contributions are welcome to enhance the project further!

# Computer Vision Project: Dataset Merging and Labeling

## Overview
This project focuses on merging datasets for a computer vision task using the YOLOv8 model. The goal is to prepare a comprehensive dataset for training, validating, and testing object detection models. 

## Key Steps

1. **Environment Setup**: 
   - Install necessary libraries, including `ultralytics`, `roboflow`, `opencv-python`, and `Pillow`.

2. **Dataset Acquisition**: 
   - Utilize the Roboflow API to download datasets from specified projects and versions.

3. **Dataset Merging**: 
   - Implement a function to merge multiple datasets, ensuring proper organization of training, validation, and testing splits.

4. **Label Renaming**: 
   - Rename class labels in the dataset to standardize them for model compatibility.

5. **Sample Visualization**: 
   - Visualize random samples from the dataset to verify data integrity and annotation accuracy.

## Usage
- Clone the repository and install the dependencies.
- Update the `datasets_info` with your specific Roboflow projects.
- Run the provided scripts to merge datasets and visualize samples.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License
This project is licensed under the MIT License.
