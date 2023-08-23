# Machine learning - Binary brest cancer classification using neural networks

* Python version 3.11.2
* Used libraries: TensorFlow, Scikit-learn, Pandas, Numpy, MatPlotLib
* There was used binary classification sequential neural network that utilizes the sigmoid activation function on the output neuron to obtain classification probabilities
* Model trained and tested on real dataset (CSV file)
* A total of 5 models were prepared: one works with all available data and 4 other models with only selected input attributes

* The main task is to verify that the model for classification of all provided data is well trained a can predict if the input data represents malignant or benign cancer
* The other aim is to compare whether the accuracy of the model is affected by the quantity and type of input data and if model working with all available data has higher accuracy and lower loss then other models working only with selected input attributes

* Results: A low loss value and high accuracy are generally positive indicators that model for classification of all provided data is well trained a can predict if the input data represents malignant or benign cancer
* All other 4 models have relatively low loss values, indicating that the models are fitting the training data well and achieving minimal prediction errors. The higher accuracy values suggest that the models are correctly classifying the input data

* On the other hand in my opinion the number of input data in this study is quite low and for more accurate evaluation of the function of the prepared models it should be many times higher
