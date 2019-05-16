## Overview

This is the source code for a sensor-based human activity recognition android app. The model has been built with Keras deep learning library. The classifier has been trained and validated on "Sensors Activity Dataset" by Shoaib et al. which is available for download from [here](https://www.utwente.nl/en/eemcs/ps/research/dataset/). The dataset contains data for seven activities of daily living including biking, downstairs, jogging, sitting, standing, upstairs, and walking. An **LSTM** learner has been employed for classification task which achieved an accuracy of **98%** on valdiation data. Finally the model has been exported in **protobuf** format to be used in android app for **on-device inference**. You can check out the jupyter notebook that goes along to follow all the steps which have been taken to build and export the model.

## Screenshots

<img src="https://user-images.githubusercontent.com/34622266/57836739-9f402a80-77d6-11e9-9617-c6c47b08ad45.jpg" width="480" height="854">

## Dependencies

- Python 3.6 <br/>
- Tensorflow 1.13.1
- Keras <br/>

## Instructions

Download [Android Studio](https://developer.android.com/studio) and then import the android app. The trained model has been inculded in the assets folder of the android app. Since I've placed the dependencies in the build.gradle file, they should be automatically downloaded.
