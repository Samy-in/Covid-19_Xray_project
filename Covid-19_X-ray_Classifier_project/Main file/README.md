# Covid-19_Xray_Classifier


At the moment, we are facing with one of the most crisis public health around the World, called Covid-19 pandemic. The F0 case was first reported in india. Now the pandemic threads all people lives as well as ecomoic collapse in most countries in the World.
To help physicians in the battles, I apply various deep learning to classify chest X-ray images from patients who are suspected to infect Covid-19.
I hope that the computer-aided tool can be robust, fast, and accurate diagnosis lungs images of Covid-19 infection, other pneumonia, and normal as well. 
Three models with transfer learning were trained with a public dataset of chest X-ray images to create classifiers. However, each trained model does not reach 100% accuracy so we apply ensemble voting method to increase both sensitivity and specificity for the overall classifier.

* Checkpoints of the models are loaded, found: [models.py](https://github.com/linhduongtuan/Covid-19-Xray-Classifier/blob/master/commons.py) 

`python app.py`     


This will firstly download the models and then start the local web server.

now go to the local server something like this - http://127.0.0.1:5000/ and see the result and explore.


