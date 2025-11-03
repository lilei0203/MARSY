# MARSY: A multitask deep learning framework for prediction of drug combination synergy scores 

In the "Comparison between different types of models" experiment of the study "A Review of Deep Learning Approaches for Drug Synergy Prediction in Cancer", MARSY is retrained using the DrugComb dataset, and their hyperparameters are readjusted to ensure a fair comparison under consistent experimental conditions:

batchsize=64
learning rate=0.0001
epoch=200

# Requirements

In order to run the MARSY.py code, Python 3.8 need to be installed. In addition, the code uses the following python modules/libraries which also need to be installed:

- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Keras](https://keras.io/)
- [Tensorflow](https://www.tensorflow.org/)

# Running MARSY

The MARSY [file](MARSY.py) provided contains a basic implementation of MARSY. The code first reads the provided data files and then, uses a data preparation function that converts the input data sets into the appropriate format. It is also composed of the implementation of the deep multitask neural network. The parameters of this model are set in the code following our design choices. Finally, an implementation of the training and a prediction example are also added.

To run the code, the script along with all the data files in this repository need to be in the same folder. The parameters of the model can be changed directly in the script.
