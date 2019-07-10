Original authors have uploaded their code here https://github.com/vlawhern/arl-eegmodels

# EEGNet
PyTorch implementation of EEGNet: A Compact Convolutional Network for EEG-based Brain-Computer Interfaces

## Requirements
* Python 2
* Dataset of your own choice, works well with BCI Competition 3 Dataset 2.
* Pytorch 0.2+
* Jupyter notebook

## Usage
* GPU - 
Just ```shift+enter``` everything.
* No GPU -
Remove all ```.cuda(0)``` before running. 

## Notes
* <strike>I found ELU to work inferior, would not recommend. Linear units work better than ReLU as well.</strike>
* I found that ELU/Linear/ReLU are similar in performance. 

## Results
* BCI Competition 3 Dataset 2 - Fmeasure (0.402)

## Credits
* Original paper - https://arxiv.org/abs/1611.08024
* PyTorch documentation.

Hope this helped you. Raise an issue if you spot errors or contact sriram@ucsd.edu.
