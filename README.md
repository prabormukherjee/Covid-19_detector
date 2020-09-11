# Covid-19_detector

Detecting Covid 19, normal flu based on chest X ray report. Using ML I made a classifier that helps us detecting these disease. The model is made with pytorch and trained with the resnet18 model.    
The dataset has 3 different classes, `covid`, `viral flu` and `normal` x-ray report from various people. Using the pretrained model weight, I found on epoch 40, it gave an acc of 97% on val dataset.   
The dataset is also included with this repo. All source of python is on the notebook.
