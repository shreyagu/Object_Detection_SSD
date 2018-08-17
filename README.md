# Object Detection

We present you the object detection code which can be applied to any pre-recorded video. The method relies on a single deep neural network to generate scores to detect the presence of each object and produce a bounding box for visual identification of the object. The bounding box is scaled according to the size of the object as it moves near or farther away from the camera. 


## Team Info:
### Shreya Gupta
shreyausc@gmail.com
https://www.linkedin.com/in/shreyagu/
https://github.com/shreyagu/

### G R Ramdas Pillai
pillairamdas@gmail.com
https://www.linkedin.com/in/pillairamdas/
https://github.com/pillairamdas/

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
The following python packages are required for running the software.


[numpy](http://www.numpy.org/)

[OpenCV 3.4.1](https://github.com/opencv/opencv)

[PyTorch](https://pytorch.org/docs/stable/index.html)


### Training
Run below commands to store the trained weights
```
cd weights
wget https://s3.amazonaws.com/amdegroot-models/ssd300_mAP_77.43_v2.pth
```

## Sample Results

1. Object detection sample on an image
![alt text](https://raw.githubusercontent.com/shreyagu/ObjectDetection/master/sample_results/output.jpeg)

## Built With
[Jupyter-notebook](http://jupyter.org/) - A web-based notebook environment for interactive computing.

[Anaconda Python Cloud](https://anaconda.org/anaconda/python) - A free and open source distribution of the Python and R programming languages for data science and machine learning related applications.

## References
The COCO dataset can be downloaded [here](http://cocodataset.org/#download).


The single shot detector implementation:
[OpenCV Source](https://github.com/amdegroot/ssd.pytorch)

The effects video used here are obtained from [Pexels Videos](https://videos.pexels.com/) and should not be used for commercial purposes.

Special thanks to [Hadelin de Ponteves](https://linkedin.com/in/hadelin-de-ponteves-1425ba5b), [Kirill Eremenko](https://linkedin.com/in/keremenko), [SuperDataScience Team](https://linkedin.com/company/superdatascience)
