---
layout: post
title:  "Research: Enercage"
excerpt: "My experience at what I learned in 1.5 years"
image: "/images/enercage.png"
---


The basic premise of Enercage is this: biology, neuroscience, psychology, and other researchers often use rats as model examples. When conducting their study, researchers or their undergraduates have to watch the rats to monitor the behavior. Annotating rat behavior is really boring task, which we hoped to automate using machine learning. This was the software innovation of the rat cage, on the hardware side the cage aimed to create head-stages which monitored neural activity that were no longer tethered to the ceiling of the cage.

For this project I worked on the machine learning side, and it was my first experience with machine learning. Initially, I started with learning basic classifiers, like SVM's, and applying to them to coordinates of the rat's features, such as the head.

Over the summer, while studying abroad, I did the [Stanford Machine Learning Coursera](https://www.coursera.org/learn/machine-learning) to help with the project during the school year.

When I came back during the school year, I worked with the images themselves, creating neural networks and convolutional neural networks with tensorflow and keras. I learnt about pre-processing image data, such as using transformations to get more training data, object detection, and padding images so that they fit into a given size. I also learnt about the research process, such as using another group's paper as a baseline and replicating their work. Lastly, I learnt about the power of transfer learning with VGG16 to help classify our images, and create a convolutional neural network given our small dataset.

<h5>Technologies Used: </h5>
<ol>
  <li>Python</li>
  <li>Tensorflow and Keras</li>
  <li>OpenCV</li>
  <li>numpy</li>
</ol>
