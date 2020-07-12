# Installation and Setup Instructions for Code

Instructions for setting an environment for the code in the book are below. These instructions :

- Have been tested on MacOS 10.15 and Ubuntu 18.04.3 LTS. You may have to translate these instructions for WIndows specific vagaries
- Only cover CPU version of TensorFlow. For latest GPU install instructions, please follow <https://www.tensorflow.org/install/gpu>

Installation uses Anaconda distribution and `pip`. It is assumed that Anaconda is setup and ready to go on your machine.

**Step 1**: Create a new conda environment with Python 3.7.5

```
$ conda create -n tf21nlp python==3.7.5
```

The environment is named `tf21nlp` but feel free to use your own name and make sure you use that in the following steps. I like to prefix my environment names with the version of TensorFlow being used and I suffix a 'g' if that environment has GPU version of the library. As you can probably infer, we are going to use TensorFlow 2.1

**Step 2**: Activate the environment and install the following packages

```
$ conda activate tf21nlp
$  conda install pandas==1.0.1 numpy==1.18.1
```

This installs Numpy and Pandas the libraries in newly created environment.

**Step 3**: Install TensorFlow 2.1 . To do this, we will need to use pip. As of writing, conda was still at 2.0\. TF has been moving quite fast. In general, conda distributions a little behind the latest versions.

```
(tf21nlp) $ pip install tensorflow==2.1
```

**Step 4**: Install Jupyter notebook - feel free to install the latest versions:

```
(tf21nlp) $ conda install Jupyter
```

Rest of the installation instructions are about specific libraries used in specific chapters. If you have trouble installing through Jupyter Notebook, you can install from command line.

## Chapter 2 Installation Instructions

Following libraries are needed for this chapter:

```
(tf21nlp) $ pip install tensorflow_datasets
```

We will `tfds` in most of the chapters going forward.

## Chapter 3 Installation Instructions

## Chapter 4 Installation Instructions

TBD

## Chapter 5 Installation Instructions

TBD

## Chapter 6 Installation Instructions

TBD

## Chapter 7 Installation Instructions

TBD

## Chapter 8 Installation Instructions

TBD

## Chapter 9 Installation Instructions

TBD