# Marine-Species-Classification

Dataset:
https://data.mendeley.com/datasets/n3ydw29sbz/3

Sample Image of datasets: 
![Catla-Body (1)](https://user-images.githubusercontent.com/47457585/210493033-bf5690bd-b2aa-4a35-a8bc-d498f780ce2b.JPG)


# Preprocessing: 
The images are enhanced using CLAHE algoerithm to overcome the lighting issues and all the images are reshaped to 512 x 512.

# Processed numpy array
Data File: https://drive.google.com/file/d/1TzUhr6LDvB2SS1Pt4HgqMT2BuINNI2nE/view?usp=share_link
Labels : https://drive.google.com/file/d/1Bgv1y2b5qd73Xxy2QUauVhG9GvHTdxp3/view?usp=share_link

These pre-processed images are trained using ResNet 50 architecture and the training accuracy is: .93, evaluation accuracy is: 0.54 and test accuracy is: 0.59
