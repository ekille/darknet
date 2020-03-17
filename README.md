![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

# Darknet #
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).

# This fork
Adds the ability to specify a list of files to run in batch. And prints out the parameters of the bounding box for each object found.

Example: 

    `./darknet detect cfg/yolov3.cfg yolov3.weights -list filelist.txt`

where `filelist.txt` is a text file containing the list of image files to be analyzed.

