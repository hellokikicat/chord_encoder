# Visualizing Midi through Auto-Encoder

This project aims to encode patterns in music notes (chords) in multi-instrument music scores by means of auto-encoder.

PyTorch is used for building NN autoencoder.

If the demo notebook failed to render in Github. There's a [rendered html](https://hellokikicat.github.io/chord_encoder/) with music playback.

Training data comes from [LAKH PIANOROLL DATASET](https://salu133445.github.io/lakh-pianoroll-dataset/dataset)

The trained encoder encodes 5-track music scores (in pianoroll format from midi files) which looks like this:

![alt text](https://raw.githubusercontent.com/hellokikicat/chord_encoder/master/imgs/pianoroll0.png) 

to something like this:

![alt text](https://raw.githubusercontent.com/hellokikicat/chord_encoder/master/imgs/encoding0.png) 

### More sample encodings:

![alt text](https://raw.githubusercontent.com/hellokikicat/chord_encoder/master/imgs/midi_00100.png) 

![alt text](https://raw.githubusercontent.com/hellokikicat/chord_encoder/master/imgs/midi_02100.png) 

![alt text](https://raw.githubusercontent.com/hellokikicat/chord_encoder/master/imgs/midi_07400.png) 

![alt text](https://raw.githubusercontent.com/hellokikicat/chord_encoder/master/imgs/midi_09200.png) 

![alt text](https://raw.githubusercontent.com/hellokikicat/chord_encoder/master/imgs/midi_00700.png) 

![alt text](https://raw.githubusercontent.com/hellokikicat/chord_encoder/master/imgs/midi_07200.png) 

![alt text](https://raw.githubusercontent.com/hellokikicat/chord_encoder/master/imgs/midi_08400.png) 

![alt text](https://raw.githubusercontent.com/hellokikicat/chord_encoder/master/imgs/midi_09800.png) 
