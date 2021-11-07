# Udacity-DeepLearning-project-Landmark-Classification-Tagging-for-Social-Media


### Table of contents

1. [Libraries used](#Libraries)
2. [Project Inspiration](#Inspiration)
3. [File Descriptions](#files)
4. [Data Insights](#Insights)
5. [Licensing, Authors, and Acknowledgements](#licensing)


## Libraries used <a name="Libraries used"></a>

Python version 3.0.
You need to install the following Python modules to complete this project:
- [cv2](https://docs.opencv.org/4.5.2/)
- [matplotlib](https://matplotlib.org/)
- [numpy](https://numpy.org/)
- [PIL](https://pillow.readthedocs.io/en/stable/)
- [torch](https://pytorch.org/)
- [torchvision](https://pytorch.org/vision/stable/index.html)


## Project Inspiration<a name="Inspiration"></a>

Photo sharing and photo storage services like to have location data for each photo that is uploaded. Service provider can build up advanced feature with location data. However, GPS is not always available, so this project is building models to automatically predict the location of the image based on any landmarks depicted in the image.
There are two models, one is built from scratch, another one is transfer leanrning model [vgg16](https://keras.io/api/applications/vgg/)

## File Descriptions <a name="files"></a>

*__landmark.ipynb__* : Jupyter notebook containing all the codes and results

*__landmark.html__* :  HTML form of the notebook

## Insights<a name="insights"></a>

Detail can be found in the notebook. In a word, random guess has 2% accuracy, model built from scartch has 29% accurancy, and transfer learning model has 75% accuracy. So its quite useful so far. 

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Data : [on Kaggle](https://www.kaggle.com/google/google-landmarks-dataset)
