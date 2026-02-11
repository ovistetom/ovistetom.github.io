# Multi-Channel Speech Enhancement Database: Mix of EARS and WHAM

## Database of clean and noisy speech samples

We present samples from __MIX-EARS-WHAM__, the database we developed to train and evaluate multi-channel speech enhancement methods.
This database was created using the [`Python`](https://www.python.org/) programming language and the [`pyroomacoustics`](https://pyroomacoustics.readthedocs.io/) library.

We mixed clean-speech audio signals from the Expressive Anechoic Recordings of Speech ([EARS](https://sp-uhh.github.io/ears_dataset/)) dataset, and ambient-noise audio signals from the WSJ0 Hipster Ambient Mixtures ([WHAM!](http://wham.whisper.ai)) dataset.
Signals from EARS were filtered with a biquad highpass filter (cut-off 70 Hz) to remove low-frequency noise.

Here, we report signals with __2__ channels, in order for the listener to assess the stereophonic properties of the signals.

## Sample 1: _SIR = +6 dB, SNR = +6 dB_

| Noisy Mixture | Clean Speech | Overall Noise |
| :---: | :---: | :---: |
| ![PNG](./data/01087/noisy_mixture.png) | ![PNG](./data/01087/target_speech.png) | ![PNG](./data/01087/overall_noise.png) |
| <audio controls> <source src="./data/01087/noisy_mixture.mp3" type="data/mpeg"> </audio> | <audio controls> <source src="./data/01087/target_speech.mp3"\> </audio> | <audio controls> <source src="./data/01087/overall_noise.mp3" type="data/mpeg"> </audio> |

<center><img src="./data/01087/room_layout.png" width="50%"></center>

## Sample 2: _SIR = 0 dB, SNR = +6 dB_

| Noisy Mixture | Clean Speech | Overall Noise |
| :---: | :---: | :---: |
| ![PNG](./data/00715/noisy_mixture.png) | ![PNG](./data/00715/target_speech.png) | ![PNG](./data/00715/overall_noise.png) |
| <audio controls> <source src="./data/00715/noisy_mixture.mp3" type="data/mpeg"> </audio> | <audio controls> <source src="./data/00715/target_speech.mp3" type="data/mpeg"> </audio> | <audio controls> <source src="./data/00715/overall_noise.mp3" type="data/mpeg"> </audio> |

<center><img src="./data/00715/room_layout.png" width="50%"></center>

## Sample 3: _SIR = +6 dB, SNR = -6 dB_

| Noisy Mixture | Clean Speech | Overall Noise |
| :---: | :---: | :---: |
| ![PNG](./data/00359/noisy_mixture.png) | ![PNG](./data/00359/target_speech.png) | ![PNG](./data/00359/overall_noise.png) |
| <audio controls> <source src="./data/00359/noisy_mixture.mp3" type="data/mpeg"> </audio> | <audio controls> <source src="./data/00359/target_speech.mp3" type="data/mpeg"> </audio> | <audio controls> <source src="./data/00359/overall_noise.mp3" type="data/mpeg"> </audio> |

<center><img src="./data/00359/room_layout.png" width="50%"></center>

## Sample 4: _SIR = 0 dB, SNR = -6 dB_

| Noisy Mixture | Clean Speech | Overall Noise |
| :---: | :---: | :---: |
| ![PNG](./data/00285/noisy_mixture.png) | ![PNG](./data/00285/target_speech.png) | ![PNG](./data/00285/overall_noise.png) |
| <audio controls> <source src="./data/00715/noisy_mixture.mp3" type="data/mpeg"> </audio> | <audio controls> <source src="./data/00715/target_speech.mp3" type="data/mpeg"> </audio> | <audio controls> <source src="./data/00715/overall_noise.mp3" type="data/mpeg"> </audio> |

<center><img src="./data/00285/room_layout.png" width="50%"></center>
