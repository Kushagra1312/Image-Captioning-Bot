# Image-Captioning-Bot

The Model generates Captions for an image.

# Dataset
I have used the Flickr8k Dataset which is available on kaggle. It had around 8K images and there were 5 captions corresponding to each image.

# Model insights
1. Image model: for reducing image of high dimensions into selected features.

2. Language model: for generating captions corresponding to the image.

3. Final model: concatenates the  results of both this model and uses LSTM layer with pretrained glove.6B.50d embedding.

