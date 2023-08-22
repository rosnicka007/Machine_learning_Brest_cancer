# Machine learning - Binary brest cancer classification using neural networks

* Python version 3.11.2
* Used libraries: TensorFlow, Scikit-learn, Pandas, Numpy, MatPlotLib
* There was used binary classification sequential neural network that utilizes the sigmoid activation function on the output neuron to obtain classification probabilities
* Model trained and tested on real dataset (CSV file)
* A total of 4 models were prepared: one works with all available data and 3 other models with only selected columns (attributes).
* The aim is to compare whether the accuracy of the model is affected by the quantity and type of input data.

* Results: A low loss value and high accuracy are generally positive indicators that these models are performing well on the given data
* All models have relatively low loss values, indicating that the models are fitting the training data well and achieving minimal prediction errors. The higher accuracy values suggest that the models are correctly classifying the data.

* It's interesting that the models focusing on individual variables ('Radius Mean', 'Smoothness Mean', 'Concavity Mean') achieved similar loss and accuracy values compared to the model for all data. This might indicate that these variables have a strong impact on the final classification (and that my vet's prediction was correct ;-) ).
