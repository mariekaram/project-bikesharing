# Predicting Bike-Sharing

In this project, I have built a simple neural network from scratch to carry out a prediction problem on a real dataset! By building a neural network from the ground up, I had a much better understanding of gradient descent, backpropagation, and other concepts that are important to know before moving to higher level tools such as PyTorch.

The data comes from the UCI Machine Learning Database "https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset".

This dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012. The number of riders is split between casual and registered, summed up in the cnt column.


## Prerequisites:

- Python 3.7
- Numpy 
- Pandas
- Matplotlib
- Jupyter Notebook
- PyTorch

## Environment:
- Anaconda

## Installing:
```
conda install -c conda-forge numpy
conda install -c conda-forge pandas
conda install -c conda-forge matplotlib
pip install torchvision
conda install -c pytorch pytorch
```
## Running the project:
The whole project is located in the jupyter notebook file `Predicting_bike_sharing_data.ipynb` and it's include the training an the prediction part. The neural network is implemented in the file `my_answer.py` and used from the jupyter notebook.

## Parameters of training:
To change to interations, the amount of hidden notes and some other parameters for the neural network, you can adapt these global constants inside the python file `my_answer.py` and watch the results.
```
# Set your hyperparameters here
iterations = 11000
learning_rate = 0.85
hidden_nodes = 17
output_nodes = 1
```
