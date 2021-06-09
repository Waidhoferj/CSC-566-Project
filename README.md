# Augmented-Reality Filters via Facial Landmark Detection

A survey of four machine learning approaches to facial landmark detection:

- [Extended Basic Model](https://github.com/Waidhoferj/CSC-566-Project/tree/main)
- [VGG Transfer Learning Model](https://github.com/Waidhoferj/CSC-566-Project/tree/vgg-transfer-learning)
- [Heatmap Model](https://github.com/Waidhoferj/CSC-566-Project/tree/heatmaps)
- [Practical Facial Landmark Detector (PFLD)](https://github.com/Waidhoferj/CSC-566-Project/tree/PFLD)

## Setup

These notebooks are intended to be run in [Google Colab](https://colab.research.google.com) with a facial landmark dataset mounted in your Google Drive. You can open this repository from Colab using [this method](https://stackoverflow.com/questions/62596466/how-can-i-run-notebooks-of-a-github-project-in-google-colab).

The code expects a folder structure in the following format:

- **CSC 566 Project**: Root folder
  - **webCamData**: videos for testing model on webcam footage.
  - **models**: Saved models
  - **datasets**
    - [**300W-3D**](http://www.cbsr.ia.ac.cn/users/xiangyuzhu/projects/3DDFA/main.htm)
    - **tf-datasets**: 300W-3D data converted into TFRecords using the OptimizedDataLoading script.

The root filename does not matter. To point the loading scripts at the correct project folder location, update the `PROJECT_FILEPATH` global variable in the Notebook.
