Encoder-Decoder Architecture: I utilized transfer learning to generate image features by feeding the images into a pre-trained Inception-v3 model, then caption sequences were generated by inputting text into a word embedding layer and feeding the resultant output into a subsequent long short-term memory (LSTM) layer
Data: Flicker8k dataset https://www.kaggle.com/hsankesara/flickr-image-dataset
