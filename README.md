# VQA

Problem Statement
  ● Our goal is to develop a machine learning model to answer any question
    posed on any given image using only the features in the image.
    
Dataset
  ● We will use VizWiz dataset containing arround 20k for training, 4k for
    validation and 8k for testing
  ● Each image/question pair has approximately 10 answers.
  ● We will use a small subset of the dataset since we don’t have enough
    computation resources.

Model
  ● Our input will be the image and the question as seen in the figure above
  ● Our model will be constituted of 3 major parts CNN, RNN, and Fully connected network
  ● And the output layer is the classification layer more precisely the output layer will
    generate a probability distribution on the given vocab
  
○ implement every component from scratch except CNN (VGG) and Embedding
layer (BOW) used for RNN.
○ Train the model once using random weight initialization for both CNN and the
embedding layer.
○ Use pre-trained weights for embedding and pre-trained weights for VGG on
imagnet.
