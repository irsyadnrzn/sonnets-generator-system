# Sonnet Generator System
## Overview
This Project is part of TensorFlow Developer Profesional Spealization conducted by DeepLearning.AI as a final project on the third courses of this series, Natural Language Processing in TensorFlow.<br> 
This Project aims to create shakespeare style Sonnet Generator System using Bidirectional LSTM. 

## Dataset
The model trained using txt file contains of 2158 lines of sonnets created by shakespeare. The dataset can be open [here](https://github.com/irsyadnrzn/sonnets-generator-system/blob/main/sonnets.txt#L2158)

## Model Architecture and Train
The Neural Network model consists of 1 Embedding Layer, 1 LSTM Layer and 1 Output Layer using SoftMax Activation Function. Image bellow show the architecture of the neural network.<br> 
<img src="https://github.com/irsyadnrzn/sonnets-generator-system/blob/main/model_architecture.png" width=50% height=50%> <br>
The model trained using adam optimizer loss function on 50 Epochs and gained 84.9% accuracy. The saved h5 model can be accessed [here](https://github.com/irsyadnrzn/sonnets-generator-system/blob/main/poem_model.h5)
