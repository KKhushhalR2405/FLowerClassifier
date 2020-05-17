# FLowerClassifier
Flower species classifier using Transfer learning

A Flower classifier using a previously trained network.
In this notebook, I have used VGGNet trained on the ImageNet dataset as a feature extractor.
VGGNet is great because it's simple and has great performance, coming in second in the ImageNet competition. The idea here is to keep all the convolutional layers, but replace the final fully-connected layer with my own classifier. This way we can use VGGNet as a fixed feature extractor for our images then easily train a simple classifier on top of that.

Steps:
1) Use all but the last fully-connected layer as a fixed feature extractor.
2) Define a new, final classification layer and apply it to a task of our choice!

