# Semantic Segmentation
### Introduction
In this project the pixels of a road in images are labelled using a Fully Convolutional Network (FCN). The network uses the architecture described in [Fully Convolutional Networks for Semantic Segmentation](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf) and is trained on the [Kitti Road](http://www.cvlibs.net/download.php?file=data_road.zip) dataset.


[//]: # (Image References)
[image6]: ./runs/1523530343.2653244/um_00002.png
[image1]: ./runs/1523530343.2653244/um_000032.png
[image2]: ./runs/1523530343.2653244/um_000093.png
[image3]: ./runs/1523530343.2653244/umm_000032.png
[image4]: ./runs/1523530343.2653244/umm_000063.png
[image5]: ./runs/1523530343.2653244/uu_000082.png
[image7]: ./runs/1523530343.2653244/um_000006.png
[image8]: ./runs/1523530343.2653244/um_000011.png

Few of the results are shown below:

![sample][image1]
![sample][image3]
![sample][image5]
![sample][image7]
![sample][image8]


### Setup
##### Frameworks and Packages
Make sure you have the following is installed:
 - [Python 3](https://www.python.org/)
 - [TensorFlow](https://www.tensorflow.org/)
 - [NumPy](http://www.numpy.org/)
 - [SciPy](https://www.scipy.org/)
##### Dataset
Download the [Kitti Road dataset](http://www.cvlibs.net/datasets/kitti/eval_road.php) from [here](http://www.cvlibs.net/download.php?file=data_road.zip).  Extract the dataset in the `data` folder.  This will create the folder `data_road` with all the training a test images.

### Start
##### Implement
Implement the code in the `main.py` module indicated by the "TODO" comments.
The comments indicated with "OPTIONAL" tag are not required to complete.
##### Run
Run the following command to run the project:
```
python main.py
```
**Note** If running this in Jupyter Notebook system messages, such as those regarding test status, may appear in the terminal rather than the notebook.

### Submission
1. Ensure you've passed all the unit tests.
2. Ensure you pass all points on [the rubric](https://review.udacity.com/#!/rubrics/989/view).
3. Submit the following in a zip file.
 - `helper.py`
 - `main.py`
 - `project_tests.py`
 - Newest inference images from `runs` folder  (**all images from the most recent run**)
 
