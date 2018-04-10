![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

# Darknet #
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).

## Usage for Pythonista
Training
```
python python/darknet_pywrapper.py --task train --cfgfilepath ${PATH_OF_CFG} --datafilepath ${PATH_OF_DATA} --weightfilepath ${PATH_OF_WEIGHTS}
```
