---
title: "Computer Vision for Recognition of Materials and Vessels in Chemistry Lab Settings and the Vector-LabPics Data Set"
collection: publications
permalink: /publication/2020-04-20-paper-title-number-1
excerpt: ''
date: 2020-04-20
venue: 'ACS Central Science'
paperurl: 'https://pubs.acs.org/doi/full/10.1021/acscentsci.0c00460'
citation: 'Eppel, Sagi, Haoping Xu, Mor Bismuth, and Alan Aspuru-Guzik. “Computer Vision for Recognition of Materials and Vessels in Chemistry Lab Settings and the Vector-LabPics Data Set.” ACS Central Science 6, no. 10 '
---

This work presents a machine learning approach for the computer vision-based recognition of materials inside vessels in the chemistry lab and other settings. In addition, we release a data set associated with the training of the model for further model development. The task to learn is finding the region, boundaries, and category for each material phase and vessel in an image. Handling materials inside mostly transparent containers is the main activity performed by human and robotic chemists in the laboratory. Visual recognition of vessels and their contents is essential for performing this task. Modern machine-vision methods learn recognition tasks by using data sets containing a large number of annotated images. This work presents the Vector-LabPics data set, which consists of 2187 images of materials within mostly transparent vessels in a chemistry lab and other general settings. The images are annotated for both the vessels and the individual material phases inside them, and each instance is assigned one or more classes (liquid, solid, foam, suspension, powder, ...). The fill level, labels, corks, and parts of the vessel are also annotated. Several convolutional nets for semantic and instance segmentation were trained on this data set. The trained neural networks achieved good accuracy in detecting and segmenting vessels and material phases, and in classifying liquids and solids, but relatively low accuracy in segmenting multiphase systems such as phase-separating liquids.
