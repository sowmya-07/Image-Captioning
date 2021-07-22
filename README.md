# Image-Captioning
This Project is about Automatic Image captioning with ConvNets and Recuurrent Nets
we use CNN Encoder and RNN Decoder to generate captions
Architecture of Neural Network consists of two parts, Encoder and Decoder. Encoder serves as a feature extractor and decoder serves for generating sequences
Neural network is trained on COCO dataset by Microsoft
The encoder uses the pre-trained ResNet-50 architecture (with the final fully-connected layer removed) to extract features from a batch of pre-processed images. The output is then flattened to a vector, before being passed through a Linear layer to transform the feature vector to have the same size as the word embedding.
![image](https://user-images.githubusercontent.com/68143886/126609028-6ed06d7c-dee0-4384-87fc-f3ccacad78ca.png)
Decoder, which is a sequential neural network consisting of LSTM units, which translates the feature vector into a sequence of tokens
![image](https://user-images.githubusercontent.com/68143886/126609138-9fc0b9bf-f612-4dee-931e-241e079f33ec.png)
![image](https://user-images.githubusercontent.com/68143886/126609730-9d03711c-afaf-4b1f-8e5c-f8dde528042d.png)
A zebra standing in a field of dry grass
