
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

## Num Features after applying a pooling layer
From keras package (keras.applications)

| Model | Features |
--- | --- | ---
|DenseNet121 | 1024|
|DenseNet169 | 1664|
|DenseNet201 | 1920|
|InceptionResNetV2 | 1536|
|InceptionV3 | 2048|
|MobileNet | 1024|
|MobileNetV2 | 1024|
|NASNetLarge | 4032|
|NASNetMobile | 1056|
|Resnet50 | 2048|
|VGG16 | 512|
|VGG19 | 512|
|Xception | 2048|


From image-classifiers package (classification_models)

| Model | Features |
--- | --- | ---
|Resnet18 | 512|
|Resnet34 | 512|
|Resnet101 | 2048|
|Resnet152 | 2048|
|Resnext50 | 2048|
|Resnext101 | 2048|
|Senet154 | 2048|
|SeResnet18 | 512|
|SeResnet34 | 512|
|SeResnet50 | 2048|
|SeResnet101 | 2048|
|SeResnet152 | 2048|
|SeResnext50 | 2048|
|SeResnext101 | 2048|


