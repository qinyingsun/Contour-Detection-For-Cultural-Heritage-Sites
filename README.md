# Contour Detection For Cultural Heritages
In this senior project, I explored different methods of contour detection in the context of cultural heritage sites, especially the Dura Europo site. With highly blurry and shadowy photos of those sites, we hope to recover the structural contours of the photos and might use them to construct 3D stroke models of the site. To achieve the goal, the contour should be complete enough to illustrate the structure of the site, but also not so detailed that irrelevant information (like the shading, material, and other objects) interfere the interpretation. This project mainly draws from conclusions of the Photo-Sketching project. 

## Setting Up
Please use the 'environment.yml' for a list of dependencies. Installing the environment using conda is recommended. 

## Checking Existing Models and Results
All of the models trained and corresponding results can be found under the '/Exp' folder

## Data and Data Pre-processing
All of the images and stroke data used can be found under the /ContourDrawing folder. The code of pre-processing is included as a jupyter notebook in the root directory. 

## Training and Testing the Models
The scripts can be found undert he scripts folder. I recommend directly changing locations (especially those pretrained locations) by revising the options file. 

## Acknowledgement
This code is based on [Photo-Sketching](https://github.com/mtli/PhotoSketch).
