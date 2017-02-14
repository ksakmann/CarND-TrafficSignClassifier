# Convolutional Neural Network for Traffic Sign Classification

## Overview

In this Udacity project for the Self-Driving Car Nanodegree I built a deep convolutional neural networks to classify traffic signs. The model is built so it can decode traffic signs from natural images. The used data set is the [German Traffic Sign Dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) and the obtained test set accuracy is 97%.  I then tested the trained model on new images of traffic signs that I found in Vienna, Austria.
Details of all individual steps are provided directly in the notebook `Traffic_Signs_Recognition.ipynb`

[//]: # (Image References)
[image1]: ./images/traffic_signs.png

![TrafficSigns][image1]


### Dependencies

This project requires **Python 3.5** and the following Python libraries installed:

- [Jupyter](http://jupyter.org/)
- [NumPy](http://www.numpy.org/)
- [SciPy](https://www.scipy.org/)
- [scikit-learn](http://scikit-learn.org/)
- [TensorFlow](http://tensorflow.org)

Run this command at the terminal prompt to install [OpenCV](http://opencv.org/). Useful for image processing:

- `conda install -c https://conda.anaconda.org/menpo opencv3`

### Getting Started

* Download the dataset. You can download the pickled dataset in which we've already resized the images to 32x32 [here](https://d17h27t6h515a5.cloudfront.net/topher/2016/October/580d53ce_traffic-sign-data/traffic-sign-data.zip).
 
* Clone the project and start the notebook.
```
git clone https://github.com/udacity/traffic-signs
cd traffic-signs
jupyter notebook Traffic_Signs_Recognition.ipynb
```
* Instructions detailing the code are provided in the `Traffic_Signs_Recognition.ipynb` notebook as well or equivalently in report.html.

