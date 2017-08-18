# Installing Librealsense & Pyrealsense on Intel® NUC DE3815TYKE

![TASS Computer Vision Demo Docs](Images/TASS-Demo-Banner.png)

## Introduction

The following information will help you install Librealsense & Pyrealsense on the Intel® Nuc DE3815TYKE.

## Install Librealsense

    $ sudo apt-get update && sudo apt-get upgrade && sudo apt-get dist-upgrade

    $ sudo apt-get install libusb-1.0-0-dev pkg-config

    $ sudo apt-get install libglfw3-dev

    $ git clone https://github.com/IntelRealSense/librealsense.git

    $ cd librealsense

    $ mkdir build && cd build

    $ cmake ../

    $ make && sudo make install

## Install Pyrealsense

    $ sudo pip install pycparser

    $ sudo pip install cython

    $ sudo sudo pip install pyrealsense



