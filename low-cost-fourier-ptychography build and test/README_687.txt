This dataset contains 256 raw Bayer images of USAF target and lung carcinoma samples obtained with red, green and blue LEDs. These images were then stitching with the codes provided into a single wide-field, high-resolution colour image using a computational imaging technique called Fourier Ptychography. Codes are provided together with simulation codes for the Raspberry Pi microscope developed by our group. Data and codes were collected/developed from June 2017 till October 2018. 

These datasets include the raw images and reconstruction codes required to replicate the full FOV reconstructions.
Details of how to run the codes are included as comments inside the code.
There are also simulation codes written in a Jupyter Notebook file with appropriate comments.

image_acquisition.py:
	This file contains a Python script required to obtain images for 
	Fourier ptychography using a Raspberry Pi computer, Raspberry Pi
	camera and Unicorn HD LED array. These images are obtained by 
	flashing LEDs in a spiral pattern from the center towards the
	edges.

scad_3dprinter_designs:
	This folder contains .scad and .stl formats of all the parts
	required to 3D print the microscope. Instructions are 
	outlined in the Supplementary material S1 of our paper.


