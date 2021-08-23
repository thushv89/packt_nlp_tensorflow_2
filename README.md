# [TensorFlow 2.0 in Action](https://www.manning.com/books/tensorflow-in-action?utm_source=thushv&utm_medium=affiliate&utm_campaign=book_ganegedara_tensorflow_10_13_20&a_aid=thushv&a_bid=a9e673f5)

This project is the code repository for [NLP TensorFlow 2.0]().

## Prerequisites (If you want GPU support)

* Install the latest NVIDIA driver for your GPU from [this page](https://www.nvidia.com/download/index.aspx?lang=en-us)
* Install CUDA 10.2 (TensorFlow 2.3)
* Setup CuDNN
* Make sure your $PATH variable contains the path to the bin folder of cuda (e.g. On Windows - C:\CUDA\v10.2\bin)
  * On UNIX - Set LD_LIBRARY_PATH to `lib64` folder (e.g. `/usr/local/cuda-10.2/lib64`)

## Creating a Virtual Environment (Anaconda) (Recommended)

* Install Anaconda
* Open up Anaconda Prompt
* Setup a conda virtual environment with `conda create -n packt.nlp.2 python=3.6`
* Activate the environment with `conda activate packt.nlp.tf2`
* Install the required libraries using `pip install -r requirements.txt`

## Important notes

* For some plotting capability provided in TensorFlow/Keras, you have installed a Python package called `graphviz`. You might need to add the path to this library (e.g. `<path to Anaconda>\envs\packt.nlp.tf2\Library\bin\graphviz` if you used Anaconda installation)

## Getting Jupyter Notebook server up

Now you are ready to run the Jupyter notebook server, allowing you to run the notebooks provided in the code repository.

* Open up the command line terminal and activate the virtual environment `packt.nlp.tf2` if you haven't already
* Go in to the directory you downloaded code to using `cd` in the CLI (e.g. `cd C:\Users\<user>\Documents\code\packt_nlp_tensorflow_2`)
* Run `jupyter notebook` in the CLI
* This should open up the jupyter notebook server's landing page on your default browser
* Now you can navigate the folder structure within that directory, open any notebook and run it.
