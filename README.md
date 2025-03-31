# Makemore-AI-Powered-Name-Generation

Library needed : PyTorch

MLP_WaveNet.ipynb contains the code of the multi layer perceptron model modified with wavenet architecture. 

Trained this model over the names data set which has 27 tokens (alphabets + '.')

With context size of 8, the model predicts names. This can be considered as a mini transformer model. 

Important points regarding the project :
1. PyTorch is only used to make the array operations efficient with usage of tensors
2. All the layers such as Linear(),BatchNorm(),Tanh() have been coded manually compatibly with pytorch so as to truly understand the torch.nn features
