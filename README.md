# Pedestrian Safety Detection System - Computer Vision & Object Detection

**IAT 360 — Exploring AI, Simon Fraser University**

A computer vision project exploring pedestrian safety through multi-class object detection at crosswalks on SFU's Burnaby campus.

Developed as a two-person team, the system uses supervised learning to identify potential pedestrian hazards, including vehicles, cyclists, traffic signals, pedestrian signals, and crosswalks.

**Features**

-Multi-class object detection for pedestrian safety

-Dataset of 3,900+ images from multiple sources

-Collection and annotation of 89 original field images across varying weather conditions

-Dataset preparation and annotation using Roboflow and Label Studio

-Model fine-tuning and hyperparameter optimization

-Performance evaluation using confusion matrices, F1-score curves, and other metrics

**Technologies**

Python · YOLO · Computer Vision · Roboflow · Label Studio

**Project Presentation and Report**

For more information about the dataset, methodology, model evaluation, challenges, and ethical considerations please view the project presentation slides and project report.

**Disclaimer**

This project was developed for educational and research purposes. It is a prototype and has not been validated for real-world pedestrian safety or autonomous navigation applications.

**Please note these are the original project instructions from the course:**

In the following 3 weeks, you will be building on your previous work with image datasets, and focus on applying the YOLO (You Only Look Once)framework to your custom dataset for your chosen task(classfication, detection, segmentation). In this tutorial we will focus on object detection only, for other tasks you will have to make few changes in notebook as well as labelled files, because each task requires specific lableling format and pre-trained models. You will fine-tune the YOLO model using the dataset you've created or annotated.Then focus on evaluating the YOLO model. You will assess its performance, discuss a potential use-case, and critically analyze its shortcomings and ethical considerations. 

**Tasks:** 
- Clone this repository
- Integrate your custom dataset into the YOLO framework (transfer learning).
- Fine-tune the YOLO model using your dataset. This involves adjusting the model's parameters to better suit your specific data.
- Conduct evaluation of your fine-tuned YOLO model. Use appropriate metrics to assess its performance (e.g., precision, recall, accuracy, F1 score, etc.). 
