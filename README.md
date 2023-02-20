# Venture Funding with Deep Learning

## Case study

A venture capital firm is looking at using Deep Learning to help them process the funding applications they get from 
startups. The company would like a Model that can predict whether applicants will be successful if funded.

The prototype Model is created in a Jupyter notebook [venture_funding_with_deep_learning](venture_funding_with_deep_learning.ipynb)
using machine learning and neural networks techniques. Then a number of visualisations are used to evaluate the 
performance of the Model.

## Data sources

- Sample data of 34,000 organizations that have received funding over the years from the venture capital firm:
[applicants_data](Resources/applicants_data.csv)

## Tasks to support the Analysis of the data

- Preparing the data for use on a neural network model.
- Compiling and evaluating a binary classification model using a neural network.
- Optimising the neural network model.

## Technical Environment
This tool utilises the following technologies:
- **Pandas** [Documentation](https://pandas.pydata.org/docs/reference/frame.html)
- **Scikit learn** [Documentation](https://scikit-learn.org/stable/)
- **Tensorflow** [Documentation](https://www.tensorflow.org/)

## Disclaimer
> Please be aware this is an Academic Case Study. The conclusions from this work should not be considered as financial 
> advice.

---
## Report

### Model 1 - performance

*HDF5 file*: [AlphabetSoup.h5](./Resources/AlphabetSoup.h5)
> 268/268 - 1s - loss: 0.5568 - accuracy: 0.7301 - 725ms/epoch - 3ms/step
> Loss: 0.5567694902420044, Accuracy: 0.7301457524299622