# Sequences-of-Objects

Sequences of Objects (SO) is a novel and effective method for ancient Chinese 'Shan Shui' painting composition classification.

This repository contains a TensorFlow implementation of SO. The repository is separated in two main parts: (1) object detector; (2) sequence classifier. Here we apply [SSD](http://arxiv.org/abs/1512.02325) as our object detector, and LSTM as our sequence classifier.

## Object detector minimal example

The [object_detection.py](object_detector/notebooks/object_detection.py) contains a minimal example of object detection pipeline.

To run:
```bash
cd object_detector/notebooks
python object_detection.py [painting_path]
```

Here are three examples of successful detection outputs:

Lofty and remote:

![](object_detector/results/lofty_and_remote.jpg)

Wide and remote:

![](object_detector/results/wide_and_remote.jpg)

Deep and remote:

![](object_detector/results/deep_and_remote.jpg)

## Sequence classifier minimal example

