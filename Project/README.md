# ME 781 Project

This project was made in a team of 4 members:
- Reet Mehta
- Abhinav Kant Mishra
- Moitreyee Sarkar
- Parag Bajaj


## Libraries Required
- python = 3.7
- pytorch = 1.10.0
- numpy
- scipy
- cv2
- matplotlib
- scikit-image
- tensorflow
- sklearn
- pickle
- random
- jupyter

## Method Details
This [Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Ulyanov_Deep_Image_Prior_CVPR_2018_paper.pdf) was implemented. We have implemented deep learning three image enhancement processes :
- Super Resolution(Reconstructs High-Resolution (HR) image from its corresponding Low-Resolution (LR) image)
- Image Inpainting(Creating or modifying pixels which also includes tasks like deblurring, text removal, artifact removal etc)
- Denoising(Process of removing noise from the Images)

We have also implemented Deblurring of Image using ML methods:
There are 3 models that we have tried out:
- SVR Regression on HSV
- SVR Regression on RGB channels separately
- Random forest regression on HSV


## Dataset
-You can include images of your choice in data folder of this repository for running DL Related solutions.
-You can include images of your choice in images folder of this repository for running ML Related solutions.

