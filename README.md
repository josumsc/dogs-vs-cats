# Dogs vs Cats: A domestic cuteness battle

This notebook addresses one of the most common tasks on Deep Learning: Object Recognition. It comes from the data presented at [this Kaggle competition](https://www.kaggle.com/uysimty/keras-cnn-dog-or-cat-classification) that presented the problem as a binary classification one, with either the object present in the photo being a cat or a dog.

We will be using Keras in order to create a Convolutional Neural Network from scratch, and TensorFlow public repository of trained models to boost up our accuracy using the architecture VGG16 trained on the famous `imagenet` dataset.

## Installation of the environment

You can follow up this notebook in your machine by downloading Anaconda and then running the following command in the terminal:

```bash
conda env create --file dogs-vs-cats.yml
```

This should have you prepared to run jupyter notebook in the terminal and then running the mentioned code using that familiar interface.

Please note that I've used a M1 Mac, so the installation might suffer from some problems if you are using a different CPU architecture. In those cases do not hesitate to look up information on the official sources such as [Tensorflow](www.tensorflow.org) or [PyPi](www.pypi.org) to solve your ocasional errors during the installation.

## References

- Deep Learning with Python - François Chollet
- Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems - Aurélien Géron
- [VGG16 Network](https://www.tensorflow.org/api_docs/python/tf/keras/applications/vgg16/VGG16)
