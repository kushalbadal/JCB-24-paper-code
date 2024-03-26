# Install and setup:
```cudatoolkit```, ``` cuDNN```, ```Tensorflow```,
```pytorch```,
```numpy```,
```matplotlib```,
```sklearn```,
```transformer```

# Auto Encoder model:
This repository contains an implementation of an autoencoder neural network architecture tailored for protein scaffold filling problem.<br>

* Autoencoder Model: The autoencoder consists of encoder and decoder components utilizing Conv1D and Conv1DTranspose layers for feature extraction and reconstruction, respectively.<br>
* Data Preprocessing: The ProteinScaffoldFixer class preprocesses protein sequence data, supports various padding types, noise injection methods, and gap-filling strategies.<br>
* Training and Evaluation: Train the autoencoder model on protein sequence data and evaluate its performance using accuracy and loss metrics.<br>
* Utility Functions: Utility functions provided for sequence visualization, file I/O, and model saving/loading.<br>

* Run autoencoder.py to train and test the model.

# Transformer Model:
* Transformer Model: The repository provides a custom implementation of the Transformer architecture specifically tailored for protein scaffold filling.<br>
* Data Preprocessing: Preprocess protein sequence data to prepare it for training and evaluation, including handling missing gaps and noise injection.<br>
* Training and Evaluation: Train the Transformer model on protein sequence data and evaluate its performance using accuracy and loss metrics.<br>
* Prediction: Utilize the trained Transformer model to generate predictions for protein sequences, filling in missing gaps and correcting errors.v

* Run Transformer.ipynb to train and test this model

# GPT2 Model:
* GPT-2 Model: This repository implements the GPT-2 (Generative Pre-trained Transformer 2) model for protein scaffold filling. <br>
* Data Preprocessing: Prepare protein sequence data for training and evaluation by preprocessing it. This includes introducing gaps and errors into the sequences to simulate real-world scenarios. The preprocessing step ensures that the model learns to handle missing information and noisy data effectively.<br>
* Training and Evaluation: Train the GPT-2 model on protein sequence data and evaluate its performance using loss and accuracy metrics. The training process involves fine-tuning the model's parameters to minimize the loss function and enhance its ability to generate accurate protein sequences.<br>
* Prediction: Utilize the trained GPT-2 model to generate predictions for protein sequences. The model can fill in missing gaps and correct errors in the sequences.<br>

* Run gpt_train.ipynb file to train and predict_sequence.ipynb file to test the model
