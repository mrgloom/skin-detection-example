# skin-detection-example

Implemented in python. Dependencies: numpy, opencv, sklearn.

Simple pixelwise skin detection using [decision tree](http://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html) [1](http://scikit-learn.org/stable/modules/tree.html#tree-algorithms-id3-c4-5-c5-0-and-cart) using pixels in RGB or HSV color space as features.

Skin Segmentation Data Set from https://archive.ics.uci.edu/ml/datasets/Skin+Segmentation

face.png image from http://graphics.cs.msu.ru/ru/node/899

Results:

![alt tag](https://github.com/mrgloom/Simple-skin-detection/blob/master/face.png)
![alt tag](https://github.com/mrgloom/Simple-skin-detection/blob/master/results/result_RGB.png) 
![alt tag](https://github.com/mrgloom/Simple-skin-detection/blob/master/results/result_HSV.png)


TODO:
~~~
Add tree visualization
https://github.com/NikTRSK/Data-Science-and-Machine-Learning-with-Python---Hands-On/blob/master/DecisionTree.ipynb
~~~
