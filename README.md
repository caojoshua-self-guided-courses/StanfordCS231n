# CS231n: Convolutional Neural Networks for Visual Recognition

These are my solutions to [Stanford's CS231n](https://cs231n.github.io/). These solutions are for the [2022 edition of the course](http://cs231n.stanford.edu/2022/).

I am going through the assignments and reading some of the course notes. These are not full solutions. I'm skipping some of the non-coding questions in the notebooks that I don't feel like answering, and I am not putting much energy the training related exercieses, resulting in lower validation and test accuracies. I am primarily focusing on better understanding the algorithms.

I provided some of my thoughts on the course in `/notes.md`.

## Setup
I am working on these locally, and not on google colab as the course recommends. I have changed the first box in each notebook to download datsets locally.

### Prerequisites

* Python (Anaconda distribution recommended for numpy, scipy, jupyter, etc.)

### Steps

Follow the [course steps to work on a local machine](https://cs231n.github.io/setup-instructions/#working-locally-on-your-machine)
```
conda create -n cs231n  # create a virtual environment
python -m notebook  # open the jupyter instance at http://localhost:8888/tree
```

It is also recommended to set up some git configuration so that jupyter notebook outputs are not committed. [[source 1](https://gist.github.com/33eyes/431e3d432f73371509d176d0dfb95b6e)], [[source2](https://stackoverflow.com/questions/28908319/how-to-clear-jupyter-notebooks-output-in-all-cells-from-the-linux-terminal)]

