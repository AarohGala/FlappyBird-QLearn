# FlappyBird-QLearn

## Dependencies

* Python 2.7 or 3
* pygame
* Anaconda
* Theano or Tensorflow
* Scipy
* numpy
* matplotlib
* pandas
* sklearn
* keras

## Running the Project

* ```git clone https://github.ncsu.edu/sgshetty/FlappyBird-QLearn.git```
* ```cd FlappyBird-QLearn```
* Install the necessary dependencies
* For using keras as backend. Change backend of keras from tensorflow to theano.
Open file ```USER/.keras/keras.json``` and change line ```“backend”: “tensorflow”``` to ```“backend” : “theano”```
* Download [dmp file](https://drive.google.com/open?id=1dUE20LMf6o4OoUtXNIiKRd3L8pRsUwz1) and store it in the same directory
* ```python playFlappy.py```


## Folder and Files Description

* assets: It contains Images which are used for the graphical enviorment of the game
* game: It contains Flappy bird game file in python. 
* graph: It contains all the graphs generated after each epoch. It also contains final Avg QMax graph.
* model: It contains files which are used for loadig and saving the variables after every epoch.

## Files

* model.h5: Store the training model after each epoch.
* playFlappy.py: This is the main file, which is used to train and play the flappy bird agent.
* plotAvgQMax.py: Plot the Avg QMax graph till the last epoch
* refresh.py: It refreshes the whole model and start from 0.



