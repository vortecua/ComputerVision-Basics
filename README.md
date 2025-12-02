# ComputerVision-Basics

Performs some basic image operations using OpenCV with Python.

## What's inside

These are just some practice scripts for learning OpenCV basics. Each file tries something different:

* **LoadingImg.py** - How to load and display images
* **LoadingVed.py** (yes, I spelled it 'ved' not 'vid') - Same but for video files/webcam feed
* **Thresholding.py** - Trying different thresholding methods
* **gradient&edge.py** - Finding edges and gradients in images
* **Featurematc.py** - Feature matching between two images
* **objrcg.py** - Simple object recognition examples
* **CreatingPoly.py** - Drawing different shapes and patterns on image feeds
* **Haarcascades_Datasets/** - Some Haar cascade files for face detection etc

## Basic idea

Most of this works with images, but same code can run on video too since video is just frames (images) playing fast. I've tried to add comments in the code where things might need changing for your setup.

## What you need

Check Requirements.txt for python packages. Main thing is you need OpenCV installed. Some scripts might need numpy too.

For installing opencv, usually this works:
```bash
pip install opencv-python
```

Some of the haar cascade stuff might need extra files - those are in the Haarcascades_Datasets folder.

## Note

This was mostly done a while back when I was learning, so some code might be messy or not the "best" way to do things. But it works for understanding the basics.

Sorry if some code is messy - this was from when I was just starting with OpenCV!
