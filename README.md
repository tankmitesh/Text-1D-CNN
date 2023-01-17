# Text-1D-CNN-Model


## Data Information and Preprocess :

#### Data have total 18828 text file, which contains documents (emails).
#### Data contains total 20 unique labels. We will classify one of the classes based on text document.
#### We extracted email id, email subject, email text from raw text data.
#### For more data insight and exploration  : Text_classification_with_1D_CNN_EDA.ipynb
#### For data preprocess : Text_classification_with_1D_CNN_Data_Preprocess.ipynb


## Model :

####  1D convolution because the kernel is moving in only one dimension: time. A single kernel will move one-by-one down a list of input embeddings, the first word embedding (and a small window of next-word embeddings) then the next word embedding, and the next, and so on. The resultant output will be a feature vector that contains about information of text then feature vector use for classification.

#### Model Notebook : Text_classification_with_1D_CNN_Modal.ipynb
