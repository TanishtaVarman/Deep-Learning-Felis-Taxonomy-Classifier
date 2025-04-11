# Deep Learning Projects: Image Classification with CNNs & Text Classification with RNNs and Transformers

## Project Overview

This repository contains my implementation of deep learning models for two main tasks: Image Classification and Text Classification. The project demonstrates the application of transfer learning, fine-tuning, and various neural network architectures to solve classification problems.

### Image Classification Task

In this task, I used the Felis Taxonomy Image Classification dataset and implemented three pre-trained CNN models:
* InceptionV3
* DenseNet121
* EfficientNetV2B0

For each model, I applied both transfer learning and fine-tuning approaches, resulting in six notebook files:
* Model1_TL.ipynb and Model1_FT.ipynb for InceptionV3
* Model2_TL.ipynb and Model2_FT.ipynb for DenseNet121
* Model3_TL.ipynb and Model3_FT.ipynb for EfficientNetV2B0

Each model was modified with specific dropout rates and batch normalization layers, and performance was evaluated using confusion matrices and precision/recall metrics.

### Text Classification Task

This task involved sentiment analysis using:
* Bidirectional versions of SimpleRNN, LSTM, and GRU models
* A transformer model with stacked encoder blocks

The implementation demonstrates the effectiveness of different neural network architectures for text classification problems.

## Technologies Used

* TensorFlow/Keras
* GPU-accelerated training
* Transfer learning & fine-tuning techniques
* Various evaluation metrics and visualization tools

*Note: All models were trained using Google Colab with GPU runtime.*
