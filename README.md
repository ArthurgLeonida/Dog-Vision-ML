# Dog-Vision-ML

## Overview
Dog breed classification is a challenging yet exciting application of machine learning. Have you ever seen a dog and wondered what breed it is? In this project, I use machine learning to identify different dog breeds based on images.

This project is based on the Kaggle Dog Breed Identification competition dataset, which contains over 10,000 labeled images across 120 different dog breeds. The task falls under multi-class image classification, meaning the model must distinguish between multiple categories rather than just two (e.g., dogs vs. cats).

## Why does this matter?

Multi-class image classification is widely used in real-world applications, including:

* Self-driving cars (identifying pedestrians, vehicles, and objects)
* E-commerce (automatic product tagging)
* Healthcare (diagnosing skin conditions from images)

## Project Workflow

The machine learning pipeline follows these steps:

1. Get data ready (download from Kaggle, store, import).
2. Prepare the data (preprocessing, the 3 sets, X & y).
3. Choose and fit/train a model (TensorFlow Hub, tf.keras.applications, TensorBoard, EarlyStopping).
4. Evaluating a model (making predictions, comparing them with the ground truth labels).
5. Improve the model through experimentation (start with 1000 images, make sure it works, increase the number of images).
6. Save, sharing and reloading your model (once you're happy with the results).

## Technologies Used

* TensorFlow 2.x – For deep learning and model training
* TensorFlow Hub – Pretrained model for transfer learning
* Matplotlib & Seaborn – Data visualization
* Pandas & NumPy – Data processing

You will need to download this folder to run the code:

https://drive.google.com/drive/folders/1Q76-8f55pMm3UWrVY_ORa2CpuBBxChod?usp=sharing

If you want to see it directly on Google Colab, here is the link:

https://colab.research.google.com/drive/1ukulgemKLd8uMpC3apFtm4rK7A9-Chuu?usp=sharing

