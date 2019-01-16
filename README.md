# ml-docker
A customized docker container including common machine learning libraries and dependencies. 

## Acknowledgements
This dockerized ml framework is by no means my sole work. Large shoutout to @waleedka for 
providing a baseline for combinging the necessary dependencies in an accessible way.

## About
This docker build contains common machine learning libraries all built to work with Python 3.5
The libraries included:

- Ubuntu 16.04 LTS
- Python 3.5.2
- Tensorflow 1.6.0
- Keras 2.1.5
- PyTorch 0.3.1
- OpenCV 3.4.1
- Jupyter Notebook
- iPython
- Numpy, Scipy, Scikit Learn, Scikit Image, Pandas, Matplotlib, Pillow
- IBM CPLEX
- Networkx

## Usage
The usage of this dockerfile clearly requires you to have docker installed:
[Docker](https://docs.docker.com/v17.12/install/). Once this is done simply run
the command below and wait as 3gb of ml libraries download pre-compiled.
```bash
docker pull mahaloz/ml-docker
```
