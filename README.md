# KaggleStatoil
Entry for the [Kaggle Statoil/C-CORE Iceberg Classifier Challenge](https://www.kaggle.com/c/statoil-iceberg-classifier-challenge), built in Python with Keras and TensorFlow.

## Summary
Created several different CNN models, which take as input 75x75 images of two channels (HH and HV). After many convolutional layers, the activation is flattened and the incidence angle (a float) is concatenated. After a few more dense layers, the output is a probability from a sigmoid activation corresponding to the probability that the image is an iceberg.

Experimented with the following architectures:
- Different sequential CNN architectures
- Resnets

Along With:
- Image augmentation
- Psuedo labelling
- Ensembling


## Result
Achieved top 14% (440/3343) on the final leaderboard, with a log loss of 0.1545.
