# ml5jsTest
A simple test of ml5.js with p5.js, for future use in SVL. A live version is available [here](https://ageller.github.io/ml5jsTest/).


I'm working mainly from the example [here](https://github.com/CodingTrain/website/tree/master/Courses/beginner_ml5/06_feature_extractor_load_save).

Also see info [here](https://github.com/ml5js/ml5-library), and examples [here](https://github.com/ml5js/ml5-examples).


Instructions:

0.  If you already have a saved training model that you want to load in, make sure that it is in your model directory, and click "load".  If you do this, you do not need to train the model, and can begin classifying by hitting the "begin" button.  If you want to train a new model, please follow the steps below.

1. Enter the number of items you want to classify against in the box labeled "Number of classes to add to training set".  Click Submit.

2. Type in the name of the first item into the box next to "record".  Place that item in front of your camera.  Hold down record for 30 seconds or so, moving the item around slowly.  This will record a picture of the item in those various positions every 0.25 seconds, add that picture to the training set, and label it with the name you typed in the box.  When you are finished, let go of the mouse button (to stop recording).  

3. Repeat step 2 for the remaining items in your training set.  (Do not exceed the number you set in step 1.)

4. Once you have entered in all your item, click "train".

5. After the model is successfully trained, you can click "begin" to start classifying items that you hold up to the webcam.  (These should ideally be the same items used in your training set.)

6.  If you want to save this training set, click the "save" button.  Then move the model.json and model.weights.bin files to your local model directory.  



Some other notes below (will clean up later)...


trying this example:
https://github.com/ml5js/ml5-examples/tree/master/p5js/ImageClassification/ImageClassification_Video

but some of the code is outdated, see here : https://ml5js.org/docs/video-classification-example

to train, see here: https://ml5js.org/docs/training-introduction

and here: https://ml5js.org/docs/FeatureExtractor

and here: https://github.com/ml5js/ml5-examples/blob/master/p5js/FeatureExtractor/FeatureExtractor_Image_Classification/sketch.js

This looks cool too: https://github.com/gitalm/EarlyFlowers/tree/master

see this: coding train : https://github.com/CodingTrain/website/tree/master/Courses/beginner_ml5

maybe this: https://github.com/CodingTrain/website/blob/master/Courses/beginner_ml5/07_knn_classifier/sketch.js

