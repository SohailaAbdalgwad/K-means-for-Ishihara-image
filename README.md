Overview
This project implements a K-means clustering algorithm from scratch to extract numbers from Ishihara color blindness test images. The algorithm segments the image into clusters based on color similarity and isolates the number by identifying the relevant clusters.

Features
Custom K-Means clustering algorithm implementation
Image segmentation capabilities
Interactive cluster selection
Visualization of individual clusters
Ability to extract and recombine selected clusters

How It Works
The program uses an unsupervised machine learning approach to group similar pixels in an image:
The image is loaded and resized to a manageable dimension (300x300)
Pixels are flattened into a 2D array where each row represents a pixel's RGB values
K-Means clustering is applied to group similar pixels together
Each cluster is visualized separately
Users can select specific clusters to recombine into a new image (e.g., to isolate objects)
