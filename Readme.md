# Sonnet Generator System

## Overview

This project is part of the TensorFlow Developer Professional Specialization conducted by DeepLearning.AI. It serves as the final project for the third course in the series, *Natural Language Processing in TensorFlow*. The goal of this project is to create a Shakespeare-style sonnet generator using a Bidirectional LSTM model.

## Dataset

The model is trained on a dataset consisting of 2,158 lines of sonnets written by William Shakespeare. This dataset provides a rich source of training material to learn the structure and style of Shakespearean sonnets. You can access the dataset and the saved model [here](https://github.com/irsyadnrzn/sonnets-generator-system/blob/main/poem_model.h5).

## Model Architecture and Training

The neural network model is built using TensorFlow and Keras and consists of the following layers:

1. **Embedding Layer**: Converts input words into dense vectors of fixed size.
2. **LSTM Layer**: A Bidirectional LSTM layer captures the context from both preceding and succeeding words in a sequence.
3. **Output Layer**: A Dense layer with a SoftMax activation function to predict the next word in the sequence.

Below is a visualization of the neural network architecture:

<p align="center">
  <img src="https://github.com/irsyadnrzn/sonnets-generator-system/blob/main/model_architecture.png" width="15%" height="15%">
</p>

### Training Details

- **Epochs**: 50
- **Optimizer**: Adam
- **Loss Function**: Categorical Crossentropy
- **Accuracy**: The model achieved an accuracy of 84.9%.

The trained model has been saved as an h5 file and is available for download [here](https://github.com/irsyadnrzn/sonnets-generator-system/blob/main/poem_model.h5).

## How to Use

1. Clone the repository:
    ```bash
    git clone https://github.com/irsyadnrzn/sonnets-generator-system.git
    ```
2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Future Work

- **Model Optimization**: Experiment with different architectures and hyperparameters to improve the quality of the generated sonnets.
- **Attention Mechanisms**: Incorporate attention mechanisms to enhance the model's ability to maintain context over longer sequences.
- **Diverse Poetry Generation**: Extend the model to generate other forms of poetry, such as haikus or limericks.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an Issue for any bugs or feature suggestions.
