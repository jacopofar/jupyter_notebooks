# Collection of Jupyter notebooks

This is a collection of Jupyter notebooks

##
To run all of them, you need Python3.6 or newer installed on the machine, then:

1. create a virtual environment with `python3 -m venv.venv`
2. activate it with `source ./venv/bin/activate`
3. run `pip3 install -r requirements.txt`
4. run Jupyter or Jupyterlab

This should work on Linux and MacOS, for Windows a few changes could are needed.

## Content:

* [coordinate to color prediction](notebooks/coordinate_to_color_prediction.ipynb) train machine learning models on an image, predicting the color given the coordinates, to get a visual representation of how they behave
* [add punctuation to a text](notebooks/add_punctuation.ipynb) use Scikit-learn, pytorch and Skorch to predict text punctuation from word embeddings. Article [here](https://jacopofarina.eu/posts/skorch-punctuation-pytorch/)
