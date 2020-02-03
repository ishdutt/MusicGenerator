# Music Generation Using Deep-Learning

## How to Run the Model
In order to run the model you can run the file " Music_Generation_Train2.ipynb"
You can also load weights which are in the file" Data2/Model_Weights/". There are total 9 weight files over there. Each weight file represents the epoch number. For instance " Weights_50.h5" are the weights saved at epoch 50. We ran our model for total of 90 epochs. 
You can add more layers into your model and fine tune the existing layers in the model. Any epoch weight can be loaded for fine tuning or "Transfer Learning".
## How to Generate Music Sequence
Once the model is defined and weights are calculated then run "Generate_Music.ipynb" file. If the architecture of your model is different than just change the architecture of the model in "make_model" function and generate music sequence.
## Type of Data:
There are total of 405 music tunes in abc notation.
## Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.
1. Python 3
2. Anaconda: It will install ipython notebook and most of the libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy, scipy.
3. keras
## Installing
1. Python 3: https://www.python.org/downloads/
2. Anaconda: https://www.anaconda.com/download/
3. Keras: pip install keras
## Built With
* ipython-notebook - Python Text Editor
* numpy, scipy- number python library
* pandas - data handling library
* Keras - Deep Learning Library

## References
https://medium.com/@gauravsharma2656/music-generation-using-deep-learning-85010fb982e2
