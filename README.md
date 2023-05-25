# neural-networks-homework
Module 13 Challenge: Venture Funding with Deep Learning

## Models
### Original model
- Data
  - Per instructions
- Layers
  - Hidden layer 1
    - 58 hidden nodes
    - `relu` activation
  - Hidden layer 2
    - 29 hidden nodes
    - `relu` activation
  - Output layer
    - 1 output neuron
    - `sigmoid` activation
- Compilation
  - 50 epochs

### Alternative model 1
Data
- Per instructions

Layers
- Hidden layer 1:
  - 58 hidden nodes
  - `relu` activation
- Hidden layer 2
  - 29 hidden nodes
  - `relu` activation
- Hidden layer 3
  - 14 hidden nodes
  - `relu` activation
- Hidden layer 4
  - 7 hidden nodes
  - `relu` activation
- Output layer
  - 1 output neuron
  - `sigmoid` activation

Compilation
- 20 epochs

### Alternative model 2
Data
- Per instructions

Layers
- Hidden layer 1:
  - 117 hidden nodes
  - `tanh` activation
- Hidden layer 2
  - 58 hidden nodes
  - `tanh` activation
- Hidden layer 3
  - 29 hidden nodes
  - `tanh` activation
- Hidden layer 4
  - 14 hidden nodes
  - `tanh` activation
- Hidden layer 5
  - 7 hidden nodes
  - `tanh` activation
- Output layer
  - 1 output neuron
  - `sigmoid` activation

Compilation
- 20 epochs

### Alternative model 3
Data
- Per instructions
- Additionally dropped `STATUS` and `SPECIAL_CONSIDERATIONS` columns

Layers
- Hidden layer 1:
  - 57 hidden nodes
  - `tanh` activation
- Hidden layer 2
  - 28 hidden nodes
  - `tanh` activation
- Hidden layer 3
  - 14 hidden nodes
  - `tanh` activation
- Hidden layer 4
  - 7 hidden nodes
  - `tanh` activation
- Output layer
  - 1 output neuron
  - `sigmoid` activation

Compilation
- 30 epochs

## Results

| Metric | Original model | Alternative model 1 | Alternative model 2 | Alternative model 3 |
|:--- |:--- |:--- |:--- |:--- |
| **Accuracy** | 0.7287 | 0.7300 | 0.7318 | 0.7331 |
| **Loss** | 0.5621 | 0.5530 | 0.5528 | 0.5542 |

## Other information
- All work for the original model and alternative models 1 and 2 can be found in the [venture_funding_with_deep_learning.ipynb](https://github.com/julianritchey/neural-networks-homework/blob/main/venture_funding_with_deep_learning.ipynb) file.
- All work for alternative model 3 can be found in the [venture_funding_with_deep_learning_model_3.ipynb](https://github.com/julianritchey/neural-networks-homework/blob/main/venture_funding_with_deep_learning_model_3.ipynb) file.
- All data used and models generated in this assignment can be found in the [Resources](https://github.com/julianritchey/neural-networks-homework/tree/main/Resources) folder.