
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

## Num Features and Parameteres after applying a pooling layer
From keras package (keras.applications)

| Model | Features | Size | Stem | input size </br>(default) | 
| --- | --- | --- | --- | --- |
|DenseNet121 | 1024| 8.1M | 7.0M | 224 |
|DenseNet169 | 1664| 14.3M | 12.6M | 224 |
|DenseNet201 | 1920| 20.2M | 18.3M | 224 |
|InceptionResNetV2 | 1536| 55.9M | 54.3M | 299 |
|InceptionV3 | 2048| 23.9M | 21.8M | 299 |
|MobileNet(alpha=1.0) | 1024| 4.3M | 3.2M | 224 |
|MobileNetV2(alpha=1.0) | 1024| 3.5M | 2.3M | 224 |
|NASNetLarge | 4032| 93.5M | 84.9M | 331 |
|NASNetMobile | 1056| 7.7M | 4.3M | 224 |
|Resnet50 | 2048| 25.6M | 23.6M | 224 |
|VGG16 | 512| 138.4M | 14.7M | 224 |
|VGG19 | 512| 143.7M |20.0M | 224 |
|Xception | 2048| 22.9M | 20.9M | 299 |


From image-classifiers package (classification_models)

| Model | Features | Size | Stem |
| --- | --- | --- | --- |
|Resnet18 | 512| 11.7M | 11.2M |
|Resnet34 | 512| 21.8M | 21.3M |
|Resnet101 | 2048| 44.6M | 42.6M |
|Resnet152 | 2048| 60.3M | 58.3M |
|Resnext50 | 2048| 25.1M | 23.0M |
|Resnext101 | 2048| 44.3M | 42.3M |
|Senet154 | 2048| 115.3M | 113.3M |
|SeResnet18 | 512| 11.8M | 11.3M |
|SeResnet34 | 512| 22.0M | 21.5M |
|SeResnet50 | 2048| 28.1M | 26.1M |
|SeResnet101 | 2048| 49.4M | 47.4M |
|SeResnet152 | 2048| 67.0M | 64.9M |
|SeResnext50 | 2048| 27.6M | 25.6M |
|SeResnext101 | 2048| 49.1M | 47.0M |


