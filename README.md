# Low-resolution Face Recognition & Identification using Super-Resolution

![readme-pic.png](readme-pic.png)

- A face recognition & identification program intended to detect & identify faces from pictures that are of size 30x30 pixels using EDSR image super-resolution.
- Achieved accuracy of at least 90% on samples across 30 distinct faces. 

- All faces have been taken from the LFW3D face samples, real-life faces are used as well
  - Take note that some personal info (especially the real-life faces) have been redacted from the samples & documentation.

## Technologies Used

- Python
- OpenCV
- EDSR (Enhanced Deep Residual Networks) image super-resolution
- Bicubic & nearest neighbor scaling

## Installation

- Download the repository and unzip it
- Install Anaconda Python IDE
- Install relevant libraries
- Select the version to run (for KNN model, use the `knn-version`; for SVM model, use the `svm-version`)
- Open the relevant `.ipynb` notebook in the folder in sequence

## Credits

- LFW3D for the faces supplied
- Mr. Geitgey for his high-resolution face recognition & identification trained model.

