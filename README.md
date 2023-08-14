# Audio_Classification
Audio Deep Learning for Sound Classification
This project demonstrates how to use deep learning to classify sounds. The dataset contains 10 classes of sounds, such as car horn, dog barking, and siren.

The first step is to load the dataset and split it into training and test sets. Then, we create a convolutional neural network (CNN) to classify the sounds. The CNN takes a mel spectrogram of the audio as input and outputs a probability distribution over the 10 classes.

We train the CNN on the training set for 10 epochs. After training, we evaluate the model on the test set and achieve an accuracy of 92%.

This project shows how deep learning can be used to classify sounds with high accuracy. It can be used to develop applications such as smart home security systems, which can detect and identify unusual sounds, or audio search systems, which can help users find specific sounds.

Dependencies:-
Python 3+
PyTorch
Torchaudio
NumPy
Pandas

Instructions
1) Clone the repository.
2) Install the dependencies.
3) Download the UrbanSound8K dataset.
4) Run the train.py script to train the model.
