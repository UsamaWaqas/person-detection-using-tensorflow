# Person Detection 👶👩🧍

Using TensorFlow 2 Detection Model Zoo, we can easily use it for person detection task.
It provides a collection of pre-trained models on the COCO 2017 dataset, which can be downloaded from [here](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md).

## 1. What is Object Detection?
Object detection is a computer vision approach for identifying and locating things in images and videos. Object detection, in particular, creates bounding boxes around identified items, allowing us to see where they are in (and how they move through) a scene.

## 2. Importance of Object Detection
Detecting objects is a critical task in computer vision. It's used in a variety of settings, including:
- Crowd counting
- Self-driving cars
- Video surveillance
- Face detection
- Person detection
- Anomaly detection

Of course, this isn't a comprehensive list, but it does include some of the most important ways that object detection is influencing our future.

## 3. How to use this repo built for Person Detection without Docker?
1. Create a new virtual environment ( Using `python -m venv venv` or `conda create -n person_detection python=3.8.6` )
2. Activate the virtual environment ( `source venv/bin/activate` or `conda activate person_detection` )
3. Install tensorflow 2 ( `pip install tensorflow==2` or `conda install -c conda-forge tensorflow` )
4. Install opencv ( `pip install opencv-python` or `conda install -c conda-forge opencv` )
5. Install numpy ( `pip install numpy` or `conda install -c conda-forge numpy` )
6. Install matplotlib ( `pip install matplotlib` or `conda install -c conda-forge matplotlib` ) - Optional
7. Install logging ( `pip install logging`)
8. Install argparse ( `pip install argparse` or `conda install -c conda-forge argparse` )



