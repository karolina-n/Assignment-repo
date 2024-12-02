# Visualizing fMRI Data for Empathy

## Author : Karolína Nováková
## Date Completed : 23.11.2024

## Source : https://neurosynth.org/analyses/terms/empathy/

## Description
This project visualizes functional magnetic resonance imaging (fMRI) data associated with empathy and it used publicly available data from Neurosynth to overlay statistical maps onto anatomical brain scans using the functional magnetic resonance imaging technique (fMRI). The project aimed at creating visualization of specific brain regions that were associated with the chosen topic “empathy”. The project also includes a histogram that visualizes the distribution of intensity values within the functional data.

## Table of Contents
1.	Introduction: Overview of the project and its goals.
   
2.	Data Used: 


•  Functional Data: Neurosynth uniformity test for “empathy”.

•  Anatomical Data: High-resolution structural MRI scan.


3.	Files in Repository
   
   
•	Notebook: Jupyter_assignment.ipynb - Contains the code for visualizing the data

•	Data Files:

o	Functional Data: uniformity_test_empathy.nii

o	Anatomical Data: anatomical_empathy.nii


4.	Code Highlights
   
   
•	Automatic file detection using glob to identify .nii files in the working directory.

•	Brain visualization using Nilearn’s plot_stat_map.

•	Histogram of positive values from functional data using Matplotlib.


5.	Python Packages
   
   
•	Python 3 (specifically version - 3.12.4)

•	Nibabel (nib): For loading .nii files and extracting numerical data

•	Nilearn (nilearn.plotting): For creating statistical overlays on anatomical MRI images

•	Matplotlib (matplotlib.pyplot): For plotting the histogram

•	NumPy (np): For handling numerical data efficiently

•	Glob : find files 

•	Pandas: Used for data handling
