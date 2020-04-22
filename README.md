# cs3244projectfinal
Repository for NUS CS3244 project. A model to predict the American Sign Language.
Using a CNN model, we were able to create a model that can process images of the American Sign Language and predict what the image represents.
Furthermore We were able to integrate a Live Testing/Prediction system. To test this live prediction see below.

# Prerequisites
Make sure you have the following installed before running:
1. Python3
1. Jupyter Notebook
1. Keras
1. numpy
1. opencv-python

# Live Testing
Make use of your webcam to test the model using your own hand.

How to do this:
1. Download the python notebook file 'ASL - Live Prediction.ipynb' located  [here](./model/)
1. Alternatively clone this entire repository, and go to the open the model/ASL - Live Prediction.ipynd folder in Jupyter Notebook
1. run all the cells
1. A new window should pop up, it should show what your webcam sees
1. Adjust the slider bars to reduce the noise. We recommend a value 80 for t1 and 120 for t2. But this varies form background to background
1. face the camera towards a clean wall
1. further adjust settings till the screen is completely black, no edges are detected
1. Then place you hand to be in the middle of the screen, and present the American Sign Language you wish to test
1. It would show its prediction as well as the coresponding probability.

# Report
click [here](./report/) for more information
