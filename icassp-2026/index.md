# ICASSP 2026 — Neural Variable Span Filters for Interpretable Speech Enhancement

## Introduction

This webpage is intended as a companion to the 2026 IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP) paper, "Neural Variable Span Filters for Interpretable Speech Enhancement".

Here, we present audio samples filtered by our proposed Hybrid Variable Span Filter (HVSF).
We present audio samples filtered by the HVSF with various multipliers applied to its _μ_ parameter, to demonstrate the effect of the multiplier on the tradeoff between speech distortion and noise reduction.

## Results

### Sample 1 (SIR = +0 dB, SNR = -4 dB)

|  | Spectrogram | Audio |
| :---: | :---: | :---: |
| Input | ![PNG](./images/00377/noisy_mixture.png) | <audio controls> <source src="./audio/00377/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| Target | ![PNG](./images/00377/target_speech.png) | <audio controls> <source src="./audio/00377/target_speech.mp3" type="audio/mpeg"> </audio> |
| Estimate (_μ_ ⨯ 1) | ![PNG](./images/00377/filtered_mu1.png) | <audio controls> <source src="./audio/00377/filtered_mu1.mp3" type="audio/mpeg"> </audio> |
| Estimate (_μ_ ⨯ 10) | ![PNG](./images/00377/filtered_mu10.png) | <audio controls> <source src="./audio/00377/filtered_mu10.mp3" type="audio/mpeg"> </audio> |
| Estimate (_μ_ ⨯ 0.1) | ![PNG](./images/00377/filtered_mu01.png) | <audio controls> <source src="./audio/00377/filtered_mu01.mp3" type="audio/mpeg"> </audio> |

### Sample 2 (SIR = +0 dB, SNR = +0 dB)

|  | Spectrogram | Audio |
| :---: | :---: | :---: |
| Input | ![PNG](./images/01049/noisy_mixture.png) | <audio controls> <source src="./audio/01049/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| Target | ![PNG](./images/01049/target_speech.png) | <audio controls> <source src="./audio/01049/target_speech.mp3" type="audio/mpeg"> </audio> |
| Estimate (_μ_ ⨯ 1) | ![PNG](./images/01049/filtered_mu1.png) | <audio controls> <source src="./audio/01049/filtered_mu1.mp3" type="audio/mpeg"> </audio> |
| Estimate (_μ_ ⨯ 10) | ![PNG](./images/01049/filtered_mu10.png) | <audio controls> <source src="./audio/01049/filtered_mu10.mp3" type="audio/mpeg"> </audio> |
| Estimate (_μ_ ⨯ 0.1) | ![PNG](./images/01049/filtered_mu01.png) | <audio controls> <source src="./audio/01049/filtered_mu01.mp3" type="audio/mpeg"> </audio> |

### Sample 3 (SIR = -3 dB, SNR = -4 dB)

|  | Spectrogram | Audio |
| :---: | :---: | :---: |
| Input | ![PNG](./images/02363/noisy_mixture.png) | <audio controls> <source src="./audio/02363/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| Target | ![PNG](./images/02363/target_speech.png) | <audio controls> <source src="./audio/02363/target_speech.mp3" type="audio/mpeg"> </audio> |
| Estimate (_μ_ ⨯ 1) | ![PNG](./images/02363/filtered_mu1.png) | <audio controls> <source src="./audio/02363/filtered_mu1.mp3" type="audio/mpeg"> </audio> |
| Estimate (_μ_ ⨯ 10) | ![PNG](./images/02363/filtered_mu10.png) | <audio controls> <source src="./audio/02363/filtered_mu10.mp3" type="audio/mpeg"> </audio> |
| Estimate (_μ_ ⨯ 0.1) | ![PNG](./images/02363/filtered_mu01.png) | <audio controls> <source src="./audio/02363/filtered_mu01.mp3" type="audio/mpeg"> </audio> |

## Database

For this experiment, signals are generated as mixtures of speech signals from the [EARS](https://sp-uhh.github.io/ears_dataset/) and noise signals from the [WHAM!](http://wham.whisper.ai) datasets, as described [here](ovistetom.github.io/mix-ears-wham/).