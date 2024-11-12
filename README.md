# Ch.-3-Computer-Vision-and-Natural-Language-Processing

This repository contains a collection of team task assignment that focused on Computer Vision such as Image Enhanching, Computer Vision using Transfer learning, and Object Detection. this team task assignment also cover Natural Language Processing for Text Classification

---

## Program Overview

### 1. Digital Image Processing [`Assignment3_No1.ipynb`](https://github.com/Xeonanda/Ch.-3-Computer-Vision-and-Natural-Language-Processing/blob/main/Assignment3_No1.ipynb)

This program involves performing various image transformations and analyses, plots the histograms, and applies CLAHE to enhance dark images. It also includes questions on Max Pooling vs CLAHE and Min vs Average Pooling. Finally, it saves the enhanced image with a new filename.

### 2. Transfer Learning with Pre - trained CNN [`Assignment3_No2.ipynb`](https://github.com/Xeonanda/Ch.-3-Computer-Vision-and-Natural-Language-Processing/blob/main/Assignment3_No2.ipynb)

This program customizes 3 different model that includes DenseNet, ResNet18, and ViT models by adjusting its architecture. It also includes questions on the impact of freezing layers on accuracy and training speed in Transfer Learning for the same epoch, batch size, and learning rate that already defined before.

### 3. Real - time Object Detection [`Assignment3_No3.ipynb`](https://github.com/Xeonanda/Ch.-3-Computer-Vision-and-Natural-Language-Processing/blob/main/Assignment3_No3.ipynb)

This program performs real - time object detection using YOLOv5 on a provided YouTube URL. It includes questions on the difference between image classification and object detection, and identifies the video with YOLOv5's lowest detection accuracy, exploring the reasons behind it.

### 4. Text Classification [`Assignment3_No4.ipynb`](https://github.com/Xeonanda/Ch.-3-Computer-Vision-and-Natural-Language-Processing/blob/main/Assignment3_No4.ipynb)

This program performs Natural Language Processing text classification to determine if a text is related to a disaster (e.g., volcano, earthquake, hurricane, etc). This program preprocess the training data by cleaning the text (e.g., removing URLs, removing HTML tags, etc), and then sets up features, label, and DataLoaders, and splits data into training and validation. This program configures batch size, number of labels, epoch, and learning rate. Finally, the program will tests the data using test data for classification

---

## How to run?

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the any of the `.ipynb` file [`Assignment3_No1.ipynb` to `Assignment3_No4.ipynb`] to Google Colab
3. If you planning to run the [`Assignment3_No1.ipynb`] make sure to upload both file on this dataset [`here`](https://drive.google.com/drive/folders/1L3oMUU3vGveJEAaLsVFA4OJXCZr8DUG7)
4. Set the GPU to T4
5. Run the code
