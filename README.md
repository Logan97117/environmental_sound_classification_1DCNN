# Classification of environmental sounds using 1D convolutional Neural network
This is an implementation of the paper https://arxiv.org/abs/1904.08990
It can deal with audio signals of any length as it splits the signal into
overlapped frames using a sliding window, hence no data augmentation is required. Different architectures considering several
input sizes are evaluated, including the initialization of the first convolutional layer
with a Gammatone filterbank that models the human auditory filter response in the
cochlea.
### Dependencies
1. NumPy v1.18
2. Tensorflow v2.2.0
3. Keras
