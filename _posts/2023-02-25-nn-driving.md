---
layout: post
title:  "Learning vision based autonomous lateral vehicle control without supervision"
place: Applied Intelligence, Springer, 2023
authors: Qadeer Khan, Idil Sülö, Melis Öcal & Daniel Cremers 
date:   2023-02-25 12:00:00 +0200
image: /images/nn-driving.png
categories: computer-vision, deep-learning
paper: https://link.springer.com/article/10.1007/s10489-023-04478-8
arxiv:
code: https://github.com/idilsulo/nn-driving/
---

![](/images/nn-driving.png)


## Abstract

Supervised deep learning methods using image data as input have shown promising results in the context of vehicle control. However, these supervised methods have two main disadvantages: 1) They require a copious amount of labeled training data, which is difficult and expensive to collect. 2) Such models do not perform well, when situations that are not in the distribution of the training set are encountered. This includes deviations from the designated driving behavior. We therefore provide a framework to mitigate these problems from merely an unlabeled sequence of images. Visual Odometry is first used to determine the vehicle trajectory. Model Predictive Control (MPC) then uses this trajectory to implicitly infer the steering labels. Meanwhile, synthesized images at deviated trajectories are included in the training distribution for enhanced robustness of the neural network model. Experimental results demonstrate that the performance of our network is at par with methods requiring additional data collection or supervision. Code and supplementary information is available here: [https://github.com/idilsulo/nn-driving](https://github.com/idilsulo/nn-driving)