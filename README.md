# DL-keras-tensorflow-projects
making some past projects public

## 2020: Deep Learning course at UofT + Band Music Chord Detector
#### 1. Multi-layer perception - [word prediction](https://github.com/gabrielle-ong/DL-keras-tensorflow-projects/blob/master/Word%20prediction.ipynb) given a sequence
#### 2. CNN: [is this a pair of shoes?](https://github.com/gabrielle-ong/DL-keras-tensorflow-projects/blob/master/CNN%20are%20shoes%20a%20pair.ipynb)
#### 3. RNN, Autoencoder: [news headlines generator](https://github.com/gabrielle-ong/DL-keras-tensorflow-projects/blob/master/news%20headline%20generator.ipynb). 
- Currently just generates the same headline, but can be extended to have text as input, headline as output
#### 4. (Exploratory fun) Music Chord detection. 
- [Audio analysis](https://github.com/gabrielle-ong/DL-keras-tensorflow-projects/blob/master/Chord%20Detection%20feature%20analysis.ipynb) to extract frequencies and notes
- Above as the basis of a custom layer to [train a model](https://github.com/gabrielle-ong/DL-keras-tensorflow-projects/blob/master/Chord%20Detection%20model%20training.ipynb). Lots of problems integrating to tflite and react native.
- Theoretically chord detection can be done via math eg fourier transform. But my application is band music with multiple instruments, improvisations and jazzy overtones. Hence tried to combine mathematical feature extraction and ML, resulting in much headache. 

## 2018: a bit GAN obsessed
#### 1. [Perspective Control in architectural Photography](https://github.com/gabrielle-ong/DL-keras-tensorflow-projects/blob/master/architectural%20photography%20perspective%20control.png). 
- In retrospect this problem should not be solved with a GAN, but a regression model to predict the degree of distortion in 3 dimensions (vertical skew, horizontal skew, rotation) and transform the image representation
- Got some pretty cool & crazy architecture photos though
#### 2. [Face Reality](https://soniasachar21.wixsite.com/facereality), sketch-to-pic GAN for forensic investigation. Won Tavtech Hackathon audience favourite.

## 2017: humble beginnings not worth mentioning but code is here.
