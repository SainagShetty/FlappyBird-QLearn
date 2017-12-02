#FlappyBird-QLearn

Folder and Files Description:
assets: It contains Images which are used for the graphical enviorment of the game
game: It contains Flappy bird game file in python. 
graph: It contains all the graphs generated after each epoch. It also contains final Avg QMax graph.
model: It contains files which are used for loadig and saving the variables after every epoch.

Files:
model.h5 -> Store the training model after each epoch.
playFlappy.py -> This is the main file, which is used to train and play the flappy bird agent.
plotAvgQMax.py -> Plot the Avg QMax graph till the last epoch
refresh.py -> It refreshes the whole model and start from 0.

Also Download https://drive.google.com/open?id=1dUE20LMf6o4OoUtXNIiKRd3L8pRsUwz1 and keep it in the folder
It contains training model data.

To Run the program. 
We need Keras or Tensorflow as backend for training Convolution Neural Network
Step 1: Download and Install Anaconda (Python 2.7 version)

Step 2: Update conda packages by typing following commands in command prompt
	conda update conda
conda update anaconda

Step 3: Make sure following packages are installed and updated to latest version, if not installed.
		Scipy, numpy, matplotlib, pandas, sklearn.

Step 4: Install Theano or Tensorflow

Step 5: Install keras, type following command into command prompt
		Pip install keras

Step 6: For using keras as backend. Change backend of keras from tensorflow to theano.
Open file USER/.keras/keras.json and change line “backend”: “tensorflow” to “backend” : “theano”

Step 7: Keep the same folder structure.

Step 8: Open command prompt in that location. Run python file by executing command
	playFlappy.py
