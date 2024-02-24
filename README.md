# Shape-Alignment-using-Template-based-Orientation-Matching

Done as part of the course SMAI/Monsoon23

Devised and implemented an innovative algorithm that leverages Principal Component Analysis (PCA) for aligning shapes within the KIMIA-99 dataset

Flowchart of Algorithm:

1. Loaded all images and selected bonefishes.png as template image
2. Computed PC1 of template image
3. For all remaining images, computed their PC1, found angle between PC1 of template image and PC1 of remaining images
4. Rotated all images clockwise or anticlockwise (using cross product)
5. Stored all output images  
