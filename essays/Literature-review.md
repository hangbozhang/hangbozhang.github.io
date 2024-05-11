---
layout: essay
type: essay
published: true
title: CNN on Object Detection in Autonomous Vehicles, A Literature Review
# All dates must be YYYY-MM-DD format!
date: 2022-05-06
labels:
  - Machine Learning
  - Self-Driving Car
  - Object Detection
---

<h3>This Literature Review is a part of the Machine Learning Project Proposal</h3>

<h3>INTRODUCTION</h3>
In the past few years, research on autonomous vehicles has attracted lots of attention. 
One of the key tasks of an autonomous vehicle is object detection and tracking, 
which is essential for intelligent decision-making in a populated area. 
Accurately detecting and tracking vehicles or pedestrians on road is essential 
for an autonomous vehicle, such that appropriate path planning and an intelligent 
decision can be made, which allows an autonomous vehicle to avoid collisions 
and ensure the safety of passengers.[1] Object detection aims to identify the 
classification and location information of a given object from complex scenes; 
such information can then be used for complicated assignments such as subsequent 
tracking of the object. Moreover, in object detection, not only must object 
classification and positioning be simultaneously identified but also the quantity 
and size of objects must be determined.[2] Convolutional neural networks (CNNs) have 
achieved high performance in the field of object detection. However, 
it requires high computational power and memory which normally is limited in
autonomous vehicles. Also, it does not support accurate detection at nighttime 
(low light conditions and lack of thermal imaging). Thus, object detection remains 
a challenging task in the field of autonomous vehicles.

In this paper, we explore and discuss different methods of object detection 
using CNN to get a better understanding and potential future avenues.

<h3>BACKGROUND</h3>
Convolutional neural network (CNN) is a class of artificial neural network in 
deep learning, most applied to analyze visual images. CNNs are regularized versions 
of multilayer perceptron. They take advantage of the hierarchical pattern in data 
and assemble patterns of increasing complexity using smaller and simpler patterns 
embossed in their filters. Therefore, on a scale of connectivity and complexity, 
CNNs are on the lower extreme.

In general, the object detection methods are grouped into two categories: 
two-stage detection, wherein a sparse set of object proposals are generated, 
and one-stage detection is a proposal-free method. Object detection models using 
deep learning are separated into the following two classes: 
regression/classification-based methods and region proposal-based methods.

<h3>The whole essay can be viewed at</h3> [Essay](../doc/literature-review.pdf)

