How to Use the program

Download and install the current version of anaconda python:

https://www.continuum.io/downloads



Create conda environment for tensorflow and python:

conda create -n tensorflow python=3.5 anaconda



Activate the tensorflow environment:

activate tensorflow



Install the following with pip:

pip install --ignore-installed --upgrade https://storage.googleapis.com/tensorflow/windows/cpu/tensorflow-1.2.1-cp35-cp35m-win_amd64.whl 

pip install Gtts

pip install Pygame



How to Install Opencv3.2.0-python3.5 to use webcam:

pip install opencv_python-3.2.0+contrib-cp35-cp35m-win_amd64.whl 

or

Go to http://www.lfd.uci.edu/~gohlke/pythonlibs/#opencv

Scroll down to OpenCV, a real time computer vision library section

Download opencv of your choice, use:

cd Download\

pip install opencv_python-3.2.0+contrib-cp35-cp35m-win_amd64.whl

or whatever version you downloaded 


Start notebook with:

(tensorflow) C:\Users\IAI>jupyter notebook



Connect your webcam

Then run the program# Image-Recognition
Real-Time Image Recognition with Speech Synthesis

@Requirements

Python 3.5

Tensorflow-gpu/cpu 1.0

Opencv 3.2

Numpy 1.12

Gtts 1.1

Pygame 1.9
