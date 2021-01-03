# Image-Captioning-Bot
## Dataset
I have used the Flickr8k Dataset which is available on Kaggle . It consists of 8k images with 5 captions for each image
## Model 
The model takes two inputs one in the form of images and another in the form of word embeddings . The Images were converted into vectors using the Pre-Trained Resnet and then used along with word embeddings to generate Captions 
The model uses LSTM and Pre-Trained Glove Word Embeddings during training and testing .
