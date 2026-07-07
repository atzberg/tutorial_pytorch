# PyTorch Basics: Tutorial

Paul J. Atzberger 
<https://web.atzberger.org/>

This is a beginner-friendly series of Jupyter notebooks covering the fundamentals of PyTorch. Topics include tensors, broadcasting, and building and training neural networks.

<p align="left">
<img src="./zdoc_img/atz_tensor_render_01.png" width="35%"> 
</p>

## Installation

We use the packages 
- Python 3.8+, [PyTorch](https://pytorch.org/get-started/locally/), Matplotlib

For a quick start use
```bash
pip install torch matplotlib
```
If this does not work then see the installation instructions on the [PyTorch website](https://pytorch.org/get-started/locally/). 

**NOTE:** No GPU is required. All examples can be run on CPU. We also provide notes pointing out in a few places how to modify the codes to use GPUs.

## Notebooks

| # | Notebook | Topics |
|---|----------|--------|
| 01 | [01_tensors.ipynb](01_tensors.ipynb) | Creating tensors, attributes, arithmetic, indexing, and reshaping |
| 02 | [02_broadcasting.ipynb](02_broadcasting.ipynb) | The four "broadcasting rules" for tensors with worked examples |
| 03 | [03_neural_networks.ipynb](03_neural_networks.ipynb) | How to use `nn.Module` for layers, forward pass, loss functions |
| 04 | [04_optimization.ipynb](04_optimization.ipynb) | Autograd, SGD, Adam, and common training loop patterns |
| 05 | [05_mlp_regression.ipynb](05_mlp_regression.ipynb) | Training a multi-layer perceptron (MLP) to fit a 2D function, "image" |

It is recommended to work through these in order since each notebook builds on concepts from the previous ones.

#### Acknowledgements 

AI Claude Sonnet 4.6 was used in our development of this tutorial series.

## Key Concepts Covered

- **Tensors**: the fundamental data structure in PyTorch, and how to create and manipulate them.
- **Broadcasting**: how PyTorch automatically aligns tensors of different shapes for element-wise operations.
- **Neural networks**: how to define layers and compose them into a model using `torch.nn`.
- **Optimization**: how gradient descent and Adam minimize a loss function, and how to write a training loop.
- **End-to-end example**: training a multi-layer perceptron (MLP) to reproduce a 2D function from (x, y) coordinate inputs, with live loss curves and side-by-side visualization.

To get started see the topic links above or go to the first notebook [[01_tensors.ipynb]](01_tensors.ipynb).
