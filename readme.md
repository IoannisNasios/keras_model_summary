
# keras models summary

This repository contains python jupyter notebooks of keras models with their summaries.
In order for someone to view a model summary, has to load the model and run model summary. As simple as it is, it can be time-consuming when you are looking for the right model and have to load one model after another.

## Summary Informations

In Keras model summary we can find informations about:
* number pamameters 
* default input size
* layer name and shape 

## Keras pretrained models origin

Keras Models are loaded either from official keras library or from classification_models library.
Keras library's collection of pre-trained models doesn' t contain some models that can be useful at this point. classification_models library contains some models that keras doesn't but also contains weights from other sources too (ex. resnet50 weights from mxnet).
