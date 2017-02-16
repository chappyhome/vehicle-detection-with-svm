# Vehicle Detection
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

In this project, my goal is to write a software pipeline to detect vehicles in a video. The project writeup can be accessed via [PDF](VehicleDetection.pdf) or [Jupyter notebook](VehicleDetection.ipynb).

The Project
---

* Perform a Histogram of Oriented Gradients (HOG) feature extraction on a labeled training set of images and train a classifier Linear SVM classifier
* Apply a color transform and append binned color features, as well as histograms of color, to my HOG feature vector. 
* Implement a sliding-window technique and use my trained classifier to search for vehicles in images.
* Run the pipeline on a video stream and create a heat map of recurring detections frame by frame to reject outliers and follow detected vehicles.
* Estimate a bounding box for vehicles detected.

I trained my vehicle image classifier this labeled data: [vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/vehicles.zip) and [non-vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/non-vehicles.zip) examples to train your classifier.  These example images come from a combination of the [GTI vehicle image database](http://www.gti.ssr.upm.es/data/Vehicle_database.html), the [KITTI vision benchmark suite](http://www.cvlibs.net/datasets/kitti/), and examples extracted from the project video itself.

## How to Run the Project

#### Clone the repo
```
git clone git@github.com:ckirksey3/vehicle-detection-with-svm.git
cd vehicle-detection-with-svm
```

#### Set up your environment
If you don't already have tools like Jupyter and OpenCV installed, follow the [Udacity instructions](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_anaconda.md) to configure an anaconda environment that will give you these tools.

#### Run the notebook
```
jupyter notebook
```

#### Walk through the steps
To see the code in practice, execute each cell in succession by pressing shift + enter.
You can also run the whole notebook in a single step by clicking on the menu Cell -> Run All.
