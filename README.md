**This is not an official Google product.**

Building a wide & deep model with the Keras Functional API
=======================

This model takes a wine's description and variety (Pinot Noir, Chardonnay, etc.) as input and predicts the price of the wine. It's built with [Keras]() using the [Functional Model API](). Here's an example input and prediction:

#### Inputs

* Description: This tremendous 100% varietal wine hails from Oakville and was aged over three years in oak. Juicy red-cherry fruit and a compelling hint of caramel greet the palate, framed by elegant, fine tannins and a subtle minty tone in the background. Balanced and rewarding from start to finish, it has years ahead of it to develop further nuance. Enjoy 2022–2030

* Variety: Cabernet Sauvignon

#### Prediction

* Price - $235

## Training the model locally

Make sure you have TensorFlow, Pandas, Scikit Learn, and Numpy installed.

I've included the model code as a Jupyter notebook (`keras-wide-deep.ipynb`). To run, first make sure you have [Jupyter]() installed. From the root directory run `jupyter notebook`. Then navigate to `localhost:8888` and click on `keras-wide-deep.ipynb`.