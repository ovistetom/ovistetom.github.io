# Neural GEVD Estimation with MWF Beamforming for Controllable Multichannel Speech Enhancement
## IEEE Open Journal of Signal Processing (OJSP) 2026

The present webpage is intended as a companion to the 
IEEE OJSP 2026 paper, [_Neural GEVD Estimation with MWF Beamforming for Controllable Multichannel Speech Enhancement_]() by T. Oviste, ... and M. G. Christensen.

Here, we present audio samples filtered by four hybrid architectures for multichannel speech enhancement, namely the CHOL+MVDR, CHOL+MWF, GEVD+MVDR and GEVD+MWF architectures studied in the publication, as represented in the figure below.
Additionally, for +MWF models, we present audio samples filtered with different post-training values for the tradeoff parameter $\mu$.
The DNN architecture leveraged for these models is the FTJNF (see publication for more details).
<center><img src="./images/modular.png" width="100%"></center>


## Sample 1 — SNR = +4 dB, SIR = +2 dB

| Model | Magnitude Spectrogram | Audio |
| :---: | :---: | :---: |
| Noisy Mixture | ![PNG](./audio/00314/noisy_mixture.png) | <audio controls> <source src="./audio/00314/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| Target Speech | ![PNG](./audio/00314/target_speech.png) | <audio controls> <source src="./audio/00314/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| __CHOL+MVDR__ | ![PNG](./audio/00314/target_speech.png) | <audio controls> <source src="./audio/00314/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| __CHOL+MWF__ ($\mu=1.0$) | ![PNG](./audio/00314/target_speech.png) | <audio controls> <source src="./audio/00314/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| __CHOL+MWF__ ($\mu=0.01$) | ![PNG](./audio/00314/target_speech.png) | <audio controls> <source src="./audio/00314/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| __CHOL+MWF__ ($\mu=10.0$) | ![PNG](./audio/00314/target_speech.png) | <audio controls> <source src="./audio/00314/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| __GEVD+MVDR__ | ![PNG](./audio/00314/target_speech.png) | <audio controls> <source src="./audio/00314/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| __GEVD+MWF__ ($\mu=1.0$) | ![PNG](./audio/00314/target_speech.png) | <audio controls> <source src="./audio/00314/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| __GEVD+MWF__ ($\mu=0.01$) | ![PNG](./audio/00314/target_speech.png) | <audio controls> <source src="./audio/00314/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| __GEVD+MWF__ ($\mu=10.0$) | ![PNG](./audio/00314/target_speech.png) | <audio controls> <source src="./audio/00314/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
