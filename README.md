# HuBMAP---Hacking-the-Human-Vasculature-FA-Major-Project
Developing a machine learning model to accurately segment microvascular structures (capillaries, arterioles, venules) in stained images of human kidney tissue.

To automate the segmentation of microvascular structures, to understand how blood vessels are organized in human tissues. This will allow us to study cellular relationships, find insights into organ function, and potentially lead to breakthroughs in understanding how these relationships impact human health.

## About Dataset
The [dataset](https://www.kaggle.com/competitions/hubmap-hacking-the-human-vasculature/data) is of a kaggle competition.

The train dataset has TIFF images each of size 512*512. The segmentation masks in JSONL format.
The train dataset has 1633 segmentation masks.

## Initial Draft
Initial Draft has the simple UNet implementation.

## Bench marking
Reduces the size of the images to 256, reduced the dataset half the size for benchmarking and trying out different models.