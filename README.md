**This is not an official Google product.**

Building a wide & deep model with the Keras Functional API
=======================

This model takes a wine's description and variety (Pinot Noir, Chardonnay, etc.) as input and predicts the price of the wine. It's built with [tf.keras](https://www.tensorflow.org/api_docs/python/tf/keras) using the [Functional Model API](https://www.tensorflow.org/api_docs/python/tf/keras/Model). Here's an example input and prediction:

#### Inputs

* Description: This tremendous 100% varietal wine hails from Oakville and was aged over three years in oak. Juicy red-cherry fruit and a compelling hint of caramel greet the palate, framed by elegant, fine tannins and a subtle minty tone in the background. Balanced and rewarding from start to finish, it has years ahead of it to develop further nuance. Enjoy 2022–2030

* Variety: Cabernet Sauvignon

#### Prediction

* Price - $235

## Training the model

You can run the model [live in Colab with zero setup here](https://colab.research.google.com/github/sararob/keras-wine-model/blob/master/keras-wide-deep.ipynb).

To run it locally, make sure you have TensorFlow, Pandas, and Jupyter installed.

I've included the model code as a Jupyter notebook (`keras-wide-deep.ipynb`). From the root directory run `jupyter notebook` to start your notebook. Then navigate to `localhost:8888` and click on `keras-wide-deep.ipynb`.

The data used for training this model is from [Kaggle](https://www.kaggle.com/zynicide/wine-reviews/data). A CSV of the data is available [here](https://www.kaggle.com/zynicide/wine-reviews/downloads/winemag-data_first150k.csv/4).