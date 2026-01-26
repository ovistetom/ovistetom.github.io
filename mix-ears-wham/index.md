# Multi-Channel Speech Enhancement Database: Mix of EARS and WHAM

## Database of clean and noisy speech samples

We present samples from __MIX-EARS-WHAM__, the database we developed to train and evaluate multi-channel speech enhancement methods.
This database was created using the [`Python`](https://www.python.org/) programming language and the [`pyroomacoustics`](https://pyroomacoustics.readthedocs.io/) library.

We mixed clean-speech audio signals from the Expressive Anechoic Recordings of Speech ([EARS](https://sp-uhh.github.io/ears_dataset/)) dataset, and ambient-noise audio signals from the WSJ0 Hipster Ambient Mixtures ([WHAM!](http://wham.whisper.ai)) dataset.

Here, we report signals with __2__ channels, in order for the listener to assess the stereophonic properties of the signals.

## Sample 1: _SIR = -6 dB, SNR = -6 dB_

| Noisy Mixture | Clean Speech | Overall Noise |
| :---: | :---: | :---: |
| ![PNG](./images/00053/y_noisy_mixture.png) | ![PNG](./images/00053/x_target_speech.png) | ![PNG](./images/00053/n_overall_noise.png) |
| <audio controls> <source src="./audio/00053/y_noisy_mixture.mp3" type="audio/mpeg"> </audio> | <audio controls> <source src="./audio/00053/x_target_speech.mp3" type="audio/mpeg"> </audio> | <audio controls> <source src="./audio/00053/n_overall_noise.mp3" type="audio/mpeg"> </audio> |

<center><img src="./images/00053/room_layout.png" width="50%"></center>

## Sample 2: _SIR = -6 dB, SNR = +6 dB_

| Noisy Mixture | Clean Speech | Overall Noise |
| :---: | :---: | :---: |
| ![PNG](./images/00056/y_noisy_mixture.png) | ![PNG](./images/00056/x_target_speech.png) | ![PNG](./images/00056/n_overall_noise.png) |
| <audio controls> <source src="./audio/00056/y_noisy_mixture.mp3" type="audio/mpeg"> </audio> | <audio controls> <source src="./audio/00056/x_target_speech.mp3" type="audio/mpeg"> </audio> | <audio controls> <source src="./audio/00056/n_overall_noise.mp3" type="audio/mpeg"> </audio> |

<center><img src="./images/00056/room_layout.png" width="50%"></center>

## Sample 3: _SIR = +6 dB, SNR = -6 dB_

| Noisy Mixture | Clean Speech | Overall Noise |
| :---: | :---: | :---: |
| ![PNG](./images/00536/y_noisy_mixture.png) | ![PNG](./images/00536/x_target_speech.png) | ![PNG](./images/00536/n_overall_noise.png) |
| <audio controls> <source src="./audio/00536/y_noisy_mixture.mp3" type="audio/mpeg"> </audio> | <audio controls> <source src="./audio/00536/x_target_speech.mp3" type="audio/mpeg"> </audio> | <audio controls> <source src="./audio/00536/n_overall_noise.mp3" type="audio/mpeg"> </audio> |

<center><img src="./images/00536/room_layout.png" width="50%"></center>

## Sample 4: _SIR = +6 dB, SNR = +6 dB_

| Noisy Mixture | Clean Speech | Overall Noise |
| :---: | :---: | :---: |
| ![PNG](./images/00102/y_noisy_mixture.png) | ![PNG](./images/00102/x_target_speech.png) | ![PNG](./images/00102/n_overall_noise.png) |
| <audio controls> <source src="./audio/00102/y_noisy_mixture.mp3" type="audio/mpeg"> </audio> | <audio controls> <source src="./audio/00102/x_target_speech.mp3" type="audio/mpeg"> </audio> | <audio controls> <source src="./audio/00102/n_overall_noise.mp3" type="audio/mpeg"> </audio> |

<center><img src="./images/00102/room_layout.png" width="50%"></center>
