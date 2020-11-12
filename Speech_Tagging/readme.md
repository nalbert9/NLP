## Introduction

In this notebook, we'll use the [Pomegranate](https://github.com/jmschrei/pomegranate) library to build a hidden Markov model for part of speech tagging with a [universal tagset](http://www.petrovi.de/data/universal.pdf). Hidden Markov models have been able to achieve >96% tag accuracy with larger tagsets on realistic text corpora. Hidden Markov models have also been used for speech recognition and speech generation, machine translation, gene recognition for bioinformatics, and human gesture recognition for computer vision, and more.

## Getting Started

**NOTE:** If you are prompted to select a kernel when you launch a notebook, choose the **Python 3** kernel.

Download the project from GitHub [here](https://github.com/nalbert9/NLP.git) and then run a Jupyter server locally with [Anaconda](https://www.anaconda.com/download/).


0. The provided code includes a function for drawing the network graph that depends on [GraphViz](http://www.graphviz.org/).

1. Open a terminal and clone the project repository:
```
$ git clone https://github.com/nalbert9/NLP.git
```

3. Switch to the project folder and create a conda environment (note: you must already have Anaconda installed):
```
$ cd Speech_Tagging
Speech_Tagging/ $ conda env create -f hmm-tagger.yaml
```

4. Activate the conda environment, then run the jupyter notebook server. (Note: windows users should run `activate hmm-tagger`)
```
Speech_Tagging/ $ source activate hmm-tagger
(hmm-tagger) Speech_Tagging/ $ jupyter notebook
```
