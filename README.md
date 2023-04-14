## Binary Classification with Tensorflow: humor detection

This project uses a dataset that consists of 200k labeled short texts (Annamoradnejad and Zoghi, 2022) to construct a binary classifier to classify humor. The classifier was built with TensorFlow convolutional neural network.

An additional classifier trained with BERT was also constructed for a comparative discussion.

The notebook consists of two parts:

**Part I : CNN model**

Part I is the core of this project. The structure of this part follows the universal workflow of machine learning in Section 4.5 in Deep Learning with Python (Chollet, 2018).

This part consists of five main sections:

* Introduction
* Developing a simple model with statistical power
* Scaling up: developing a model that overfits
* Tuning the hyperparameters
* Building the final model: Discussion and conclusion

**Part II : BERT model**

Part II documents the experiment on training a BERT model with the same dataset used in Part I. Since this is an additional experiment, this part will not follow the universal workflow. The aim of Part II is to create a small BERT model and compare its result and architecture with the final CNN model.

This part consists of four main sections:

* Introduction
* Pre-processing
* Building a BERT model
* Comparison with CNN model: Discussion and conclusion
