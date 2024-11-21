# HAR Transformer
Transformer for Human Activity Recognition

## Description

The Transformer for Human Activity Recognition operates in sequence-to-sequence mode and predicts the class for each time series feature. The advantage is that if there are several consecutive classes in one time series, these classes can be easily identified, and the transformer is not limited to the features in the whole time series belonging to one class. 



## Model

<p align="center">
  <img src="img/model.png" style="background-color: white;">
</p>

## Results

<p align="center">
  <b>Confusion matrix</b>
  <img src="img/result.png" style="background-color: white;">
</p>

<p align="center">
  <b>Hyperparameters</b>
  <img src="img/hyperparams.png">
</p>

----------------------------------

**Frameworks:** TensorFlow, NumPy, Pandas, Scikit-learn, WanDB
