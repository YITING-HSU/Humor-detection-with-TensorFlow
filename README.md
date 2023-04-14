## Binary Classification with Tensorflow: humor detection

In this project, a TensorFlow convolutional neural network was employed to build a binary classifier that can classify humor, using a dataset of [200k labeled short texts](https://arxiv.org/abs/2004.12765). A second classifier was also constructed using BERT for comparative analysis.

The notebook comprises of two sections:

**Part I : CNN model**

Part I is the center of this project. The structure of this part follows the universal workflow of machine learning in Section 4.5 in Deep Learning with Python.

This section is composed of five primary sections: 

* Introduction
* Developing a simple model with statistical power
* Scaling up: developing a model that overfits
* Tuning the hyperparameters
* Building the final model: Discussion and conclusion

**Part II : BERT model**

Part II of the project documents an experiment in which a BERT model is trained using the same dataset employed in Part I. Unlike Part I, this section will not follow the standard machine learning workflow since it is an additional experiment. The objective of Part II is to construct a compact BERT model and compare its architecture and outcomes with the final CNN model.

This section is divided into four primary sections.

* Introduction
* Pre-processing
* Building a BERT model
* Comparison with CNN model: Discussion and conclusion
