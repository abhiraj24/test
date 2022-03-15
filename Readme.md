## Introduction

1. Code to implement a FNN on MNIST dataset and check the perfomance on train and validation data.
2. The entire code has been impemented using pytorch.
3. FNN Architecture :

> ```
> Linear(in_features=784, out_features=64, bias=True)
> BatchNorm1d(64, eps=1e-05, momentum=0.1, affine=True, track_running_stats=True)
> Linear(in_features=64, out_features=32, bias=True)
> BatchNorm1d(32, eps=1e-05, momentum=0.1, affine=True, track_running_stats=True)
> Linear(in_features=32, out_features=10, bias=True)
> ```

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the packages.

```bash
pip3 install torch
pip3 install torchvision
pip3 install plotly

```

## Computational Graph
![Plot](https://github.com/abhiraj24/test/blob/main/Screen%20Shot%202022-03-15%20at%202.35.50%20AM.png?raw=true)


## Instructions to Run

1) Downlaod the file **HW01.py** and store it in a desired location.
2) From terminal run **python HW01.py**

## References

```
[1] https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html1) Downlaod the file HW01.py and store it in a desired location.
[2] https://www.kaggle.com/basu369victor/pytorch-tutorial-the-classification
[3] https://docs.microsoft.com/en-us/windows/ai/windows-ml/tutorials/pytorch-train-model
```

## Train Validation Plot

![Plot](https://github.com/abhiraj24/test/blob/main/output.png?raw=true)
