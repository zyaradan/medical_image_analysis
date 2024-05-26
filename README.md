# DICOM Visualization Project

Overview

This project involves the visualization of DICOM (Digital Imaging and Communications in Medicine) data, specifically focusing on the segmentation and animation of medical images. The provided Jupyter Notebook, Zeynep_DICOM_visualization_project.ipynb, demonstrates how to process and visualize these images, with the goal of providing clear and informative representations of the segmented anatomical structures.

Project Files

	•	Zeynep_DICOM_visualization_project.ipynb: The main Jupyter Notebook containing the code for processing and visualizing the DICOM images.
	•	segmentation_animation.gif: A GIF file showcasing the animation of segmented anatomical structures.
	•	animation_alpha_0.5.gif: A GIF file showcasing the animation of segmented anatomical structures with a specific alpha transparency setting.

Requirements

To run the Jupyter Notebook and generate the visualizations, you’ll need the following libraries:

	•	numpy
	•	pydicom
	•	matplotlib
	•	opencv-python
	•	scipy

You can install these packages using pip:
pip install numpy pydicom matplotlib opencv-python scipy

Instructions

	1.	Load the DICOM Data: The notebook will guide you through loading DICOM images using the pydicom library. Ensure you have access to the necessary DICOM files.
	2.	Preprocess the Images: The preprocessing steps include resizing, normalization, and application of filters to enhance the quality of the images.
	3.	Segmentation: The notebook demonstrates how to apply segmentation algorithms to identify and highlight specific anatomical structures within the DICOM images.
	4.	Visualization: Various visualization techniques are employed to represent the segmented structures, including 2D and 3D plotting with matplotlib.
	5.	Animation: The notebook includes sections for generating animations of the segmented structures. These animations are saved as GIF files, such as segmentation_animation.gif and animation_alpha_0.5.gif.
