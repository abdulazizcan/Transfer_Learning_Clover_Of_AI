# Medical Cost Analysis

Deep learning is one of the most popular machine learning techniques that has been extensively studied in recent years. Deep Learning models are often trained with a set of labeled data to learn representations and connections from unlabeled data. Transfer learning is the process of training a model on a large dataset and then using it for a different, typically smaller task. In this project, we trained a deep learning model with Transfer Learning using "Cats and Dogs". This study was conducted as part of Global AI Hub's AI Summer Camp'22.
 
## Model and Data

-   Data: [Kaggle Dataset](https://www.microsoft.com/en-us/download/details.aspx?id=54765).
-   [Transfer Learning Model: VGG16](https://www.tensorflow.org/api_docs/python/tf/keras/applications/vgg16/VGG16)

## Description of Files

- In first_stage.ipynb, the processes of bringing the images to the same resizing, normalization, labeling, separation of the data set as train, test, validation and recording are carried out.
- In second_stage.ipynb, training and tests were carried out using deep learning models with the previously created data set.

## Library
  - python=3.8
  - matplotlib
  - os
  - cv2
  - pickle
  - numpy
  - tensorflow
  - sklearn.model_selection


## Author 

- [Abdülaziz Can](https://github.com/abdulazizcan)
- [Ömer Yıldırım](https://github.com/omer-yildirim)
- [Tunahan Demirkol](https://github.com/TunahanDemirkol)

## License

[MIT](https://opensource.org/licenses/MIT)