# Multivariate Time Series Forecasting Artificial Neural Network
## Overview
The program is a `Python` implementation using `Jupyter Notebook` of an artificial neural network model for the prediction of multivariate time series of un unspecified nature, provided as a training set.

### Authors
<b>DEEPressi</b> Team
- <b>Tommaso Brumani</b> (tommaso.brumani@mail.polimi.it)
- <b>Riccardo Pazzi</b> (riccardo.pazzi@mail.polimi.it)
- <b>Gianluca Ruberto</b> (gianluca.ruberto@mail.polimi.it)

### License
The project was carried out as part of the 2021/2022 '<b>Artificial Neural Networks and Deep Learning</b>' course at <b>Politecnico of Milano</b>, where it was evaluated based on its accuracy over a test set and awarded a score of 5/5.

## Project Specifications
The project consisted of producing a model capable of forecasting the value of a set of multivariate time series signals the origin or nature of which was not specified, but were provided as training set.

The team was granted great freedom in choosing its approach, but encouraged to use the techniques covered in the course, including data augmentation, hyperparameter tuning, and various types of neural network structures.

In regards to the dataset provided, the team attempted to isolate the most relevant frequencies in order to reconstruct a less noisy signal, as well as superimposing random gaussian noise to the existing dataset as a form of data augmentation.

In terms of neural network structures, the team tried using LSTMs (both unidirectional and bidirectional), Transformers, Diluted Convolution, but eventually achieved the best performance with a single dense layer.  

The team attempted to employ both direct forecasting and autoregression, decreasing learning rates, early stopping, and parameter tuning using random search and bayesian search.

## Folder Structure
* `report`: the report detailing the various approaches that were tried as part of the development of the model
* `src`: the `jupyter notebook` code for the final model