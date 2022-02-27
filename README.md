# CAM for visualize what CNNs see





## Introduction

Recent work has shown that the convolutional units of various layers of convolutional neural networks (CNNs) actually behave as object detectors despite no supervision on the location of the object was provided. Despite having this remarkable ability to localize objects in the convolutional layers, this ability is lost when fully-connected layers are used for classification.
<br></br>
By replacing fully connected layers by a Global Average Pooling(GAP) layer, we can preserve these information and can also prevent overfitting. This method is known as CAM (convolutional activation map). The GAP layer enhances feature maps in the last convolutional layer to learn object locations when training for classification. Therefore, the weighted sum of those feature maps corresponds to an object

Reference: [this paper](http://cnnlocalization.csail.mit.edu/Zhou_Learning_Deep_Features_CVPR_2016_paper.pdf)



