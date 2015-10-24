# Simple-skin-detection

Implemented in python. Dependencies: numpy, opencv, sklearn.

1. Simple pixelwise skin detection using [classification tree](http://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html).

2. Histogram backprojection.

Data and tools:

1. Skin Segmentation Data Set from https://archive.ics.uci.edu/ml/datasets/Skin+Segmentation

2. face.png image from http://graphics.cs.msu.ru/ru/node/899

3. 3D projection of skin pixels was done by 3D Color Inspector/Color Histogram Tool http://imagej.net/plugins/color-inspector.html 

Some results:

![alt tag](https://github.com/mrgloom/Simple-skin-detection/blob/master/face.png)
![alt tag](https://github.com/mrgloom/Simple-skin-detection/blob/master/results/result_RGB.png) 
![alt tag](https://github.com/mrgloom/Simple-skin-detection/blob/master/results/result_HSV.png)


----------------------------------------------------------------------------------------------------------------------
TODO:
~~~
1. GMM http://www.ghvandoorn.nl/skindetection.html
2. Make demo with user input.
3. Evaluate methods on additional datasets.
4. Try other color spaces http://pesona.mmu.edu.my/~johnsee/research/papers/files/rgbhcbcr_m2usic06.pdf
~~~


DATA:
~~~
http://lbmedia.ece.ucsb.edu/research/skin/skin.htm
http://www.feeval.org/Data-sets/Skin_Colors.html
http://web.fsktm.um.edu.my/~cschan/project1.htm
~~~

PAPERS:
~~~
"A Survey on Pixel-Based Skin Color Detection Techniques"
http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.5.521&rep=rep1&type=pdf
"Statistical Color Models with Application to Skin Detection"
http://www.hpl.hp.com/techreports/Compaq-DEC/CRL-98-11.pdf
~~~
