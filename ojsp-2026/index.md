# Neural GEVD Estimation with MWF Beamforming for Controllable Multichannel Speech Enhancement
## IEEE Open Journal of Signal Processing (OJSP) 2026

The present webpage is intended as a companion to the 
IEEE OJSP 2026 paper, [_Neural GEVD Estimation with MWF Beamforming for Controllable Multichannel Speech Enhancement_]() by T. Oviste, ... and M. G. Christensen.

Here, we present audio samples filtered by four hybrid architectures for multichannel speech enhancement, namely the CHOL+MVDR, CHOL+MWF, GEVD+MVDR and GEVD+MWF architectures studied in the publication, as represented in the figure below.
Additionally, for +MWF models, we present audio samples filtered with different post-training values for the tradeoff parameter $\mu$.
The DNN architecture leveraged for these models is the FTJNF (see publication for more details).
<center><img src="./images/modular.png" width="100%"></center>


## Sample 1: 

| Model | Magnitude Spectrogram | Audio |
| :---: | :---: | :---: |
| Noisy Mixture <br>(SNR = -3 dB, SIR= -1 dB)| ![PNG](./audio/01474/noisy_mixture.png) | <audio controls> <source src="./audio/01474/noisy_mixture.mp3" type="audio/mpeg"> </audio> |
| Target Speech | ![PNG](./audio/01474/target_speech.png) | <audio controls> <source src="./audio/01474/target_speech.mp3" type="audio/mpeg"> </audio> |
| __CHOL+MVDR__ | ![PNG](./audio/01474/CHOL+MVDR_filtered_mixture.png) | <audio controls> <source src="./audio/01474/CHOL+MVDR_filtered_mixture.mp3" type="audio/mpeg"> </audio> |
| __CHOL+MWF__ <br>(μ = 1.0) | ![PNG](./audio/01474/CHOL+MWF_mu10_filtered_mixture.png) | <audio controls> <source src="./audio/01474/CHOL+MWF_mu10_filtered_mixture.mp3" type="audio/mpeg"> </audio> |
| __CHOL+MWF__ <br>(μ = 0.1) | ![PNG](./audio/01474/CHOL+MWF_mu01_filtered_mixture.png) | <audio controls> <source src="./audio/01474/CHOL+MWF_mu01_filtered_mixture.mp3" type="audio/mpeg"> </audio> |
| __CHOL+MWF__ <br>(μ = 5.0) | ![PNG](./audio/01474/CHOL+MWF_mu50_filtered_mixture.png) | <audio controls> <source src="./audio/01474/CHOL+MWF_mu50_filtered_mixture.mp3" type="audio/mpeg"> </audio> |
| __GEVD+MVDR__ | ![PNG](./audio/01474/GEVD+MVDR_filtered_mixture.png) | <audio controls> <source src="./audio/01474/GEVD+MVDR_filtered_mixture.mp3" type="audio/mpeg"> </audio> |
| __GEVD+MWF__ <br>(μ = 1.0) | ![PNG](./audio/01474/GEVD+MWF_mu10_filtered_mixture.png) | <audio controls> <source src="./audio/01474/GEVD+MWF_mu10_filtered_mixture.mp3" type="audio/mpeg"> </audio> |
| __GEVD+MWF__ <br>(μ = 0.1) | ![PNG](./audio/01474/GEVD+MWF_mu01_filtered_mixture.png) | <audio controls> <source src="./audio/01474/GEVD+MWF_mu01_filtered_mixture.mp3" type="audio/mpeg"> </audio> |
| __GEVD+MWF__ <br>(μ = 5.0) | ![PNG](./audio/01474/GEVD+MWF_mu50_filtered_mixture.png) | <audio controls> <source src="./audio/01474/GEVD+MWF_mu50_filtered_mixture.mp3" type="audio/mpeg"> </audio> |
