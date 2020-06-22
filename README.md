# TV Script Generator
> Recurrent Neural Networks

This project aims at successfully generating `fake` tv scripts using recurrent neural networks

## Installing / Getting started

A quick introduction of the minimal setup you need to get the classifier up &
running.

```shell
git clone https://github.com/abhigyan2311/tv-script-generator.git
cd tv-script-generator
conda env create -f environment.yml
conda activate deeplearning
jupyter notebook dlnd_tv_script_generation.ipynb
```

## Features

The classifier notebook implements the following methods:
* Successfully generates fake tv scripts bases on [Seinfeld](https://en.wikipedia.org/wiki/Seinfeld) tv series scripts

The best minimum loss was achieved of 3.19.

## Hyperparameters

* Sequence Length - 200
* Batch Size - 128
* Number of epochs - 10
* Learning Rate - 0.001
* Embedding Dimension - 400
* Hidden Dimension - 256
* Number of RNN Layers - 2

## Contributing

"If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome."


## Licensing

"The code in this project is licensed under Apache 2.0 license."
