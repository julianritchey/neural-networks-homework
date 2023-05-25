# neural-networks-homework
Module 13 Challenge: Venture Funding with Deep Learning

## Compile and Evaluate a Binary Classification Model Using a Neural Network
### Original model
#### Details
- Hidden layers
  - Hidden layer 1
    - 58 hidden nodes
    - 'relu' activation
  - Hidden layer 2
    - 29 hidden nodes
    - 'relu' activation
- Output layer
  - 1 output neuron
  - 'sigmoid' activation
- Compilation
  - 50 epochs

#### Results
- Accuracy: **0.7287**
- Loss: **0.5621**

## Optimize the Neural Network Model
### Alternative model 1
#### Details
- Hidden layers
  - Hidden layer 1:
    - 58 hidden nodes
    - 'relu' activation
  - Hidden layer 2
    - 29 hidden nodes
    - 'relu' activation
  - Hidden layer 3
    - 14 hidden nodes
    - 'relu' activation
  - Hidden layer 4
    - 7 hidden nodes
    - 'relu' activation
- Output layer
  - 1 output neuron
  - 'sigmoid' activation
- Compilation
  - 20 epochs

#### Results
- Accuracy: **0.7300**
- Loss: **0.5530**

### Alternative model 2
#### Details
- Hidden layers
  - Hidden layer 1:
    - 117 hidden nodes
    - 'tanh' activation
  - Hidden layer 2
    - 58 hidden nodes
    - 'tanh' activation
  - Hidden layer 3
    - 29 hidden nodes
    - 'tanh' activation
  - Hidden layer 4
    - 14 hidden nodes
    - 'tanh' activation
  - Hidden layer 5
    - 7 hidden nodes
    - 'tanh' activation
- Output layer
  - 1 output neuron
  - 'sigmoid' activation
- Compilation
  - 20 epochs

#### Results
- Accuracy: **0.7318**
- Loss: **0.5528**

### Alternative model 3
#### Details
- Hidden layers
  - Hidden layer 1:
    - 57 hidden nodes
    - 'tanh' activation
  - Hidden layer 2
    - 28 hidden nodes
    - 'tanh' activation
  - Hidden layer 3
    - 14 hidden nodes
    - 'tanh' activation
  - Hidden layer 4
    - 7 hidden nodes
    - 'tanh' activation
- Output layer
  - 1 output neuron
  - 'sigmoid' activation
- Compilation
  - 30 epochs

#### Results
- Accuracy: **0.7331**
- Loss: **0.5542**

## Other information
- All work for the original model and alternative models 1 and 2 can be found in the [venture_funding_with_deep_learning.ipynb](https://github.com/julianritchey/neural-networks-homework/blob/main/venture_funding_with_deep_learning.ipynb) file.
- All work for alternative model 3 can be found in the [venture_funding_with_deep_learning_model_3.ipynb](https://github.com/julianritchey/neural-networks-homework/blob/main/venture_funding_with_deep_learning_model_3.ipynb) file.
- All data used and models generated in this assignment can be found in the [Resources](https://github.com/julianritchey/neural-networks-homework/tree/main/Resources) folder.