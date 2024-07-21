# Music generation project

This repository contains two distinct music generation projects:

ABC Notation Music Generator
Spectrogram-based Hip Hop Instrumental Generator

1. ABC Notation Music Generator
This project uses a deep learning model to generate music in ABC notation format, which is commonly used for folk and traditional music.
Features

Generates ABC notation for musical pieces
Uses a Recurrent Neural Network (RNN) architecture
Trained on a two songs from a Moroccan artist (Draganov)

Results: Altough we managed to produce a musical output, it was hard to have a natural continution for the instrumentals and this for two reasons: a small dataset as well as the fact that ABC notation cannot transcript the diversity of sounds in hip hop instrumentals

2. Spectrogram-based Hip Hop Instrumental Generator
This project uses mel spectrograms to generate hip hop instrumentals, employing a deep learning model to continue a given audio input.
Features

Generates continuation of hip hop instrumentals
Uses mel spectrograms for audio representation
Employs a CNN-LSTM architecture for generation

Results are quite good and encouraging. The output is very noisi though. We could get better results with a better training phase and also a larger dataset, but overall good results
