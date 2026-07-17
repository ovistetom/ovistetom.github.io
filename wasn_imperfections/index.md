# Simulating Synchronization Imperfections in Wireless Acoustic Sensor Networks

<!--------------------------------------->
## Sampling-Time Offset (STO)

### Waveform Example

![PNG](./images/sto.png)

### Audio Example

Audio is a speech signal from the ([EARS](https://sp-uhh.github.io/ears_dataset/)) dataset.  
The signal is stereophonic: here, the left channel is used as reference, and the STO is applied to the right channel only.

| Ideal | With STO (25 ms) |
| :---: | :---: |
| <audio controls> <source src="./audio/69_stereo.mp3" type="audio/mpeg"> </audio> | <audio controls> <source src="./audio/69_sto.mp3" type="audio/mpeg"> </audio> |

<!--------------------------------------->
## Sampling-Rate Offset (SRO)

### Waveform Example

![PNG](./images/sro.png)

Sidenote: traditional values for SRO are generally found between 0 and 100 ppm – it is exaggerated here for the sake of visualization.

### Audio Example

Audio is a speech signal from the ([EARS](https://sp-uhh.github.io/ears_dataset/)) dataset.  
The signal is stereophonic: here, the left channel is used as reference, and the SRO is applied to the right channel only.

| Ideal | With SRO (60 ppm) |
| :---: | :---: |
| <audio controls> <source src="./audio/69_stereo.mp3" type="audio/mpeg"> </audio> | <audio controls> <source src="./audio/69_sro.mp3" type="audio/mpeg"> </audio> |

<!--------------------------------------->
## Packet Loss (PL)

Packet loss is simulated using a Gilbert-Elliott probabilistic model from Chinaev et al., _Online Estimation of Sampling Rate Offsets
in Wireless Acoustic Sensor Networks with Packet Loss_, 2021.

### Waveform Example

![PNG](./images/pl.png)

### Audio Example


Audio is a speech signal from the ([EARS](https://sp-uhh.github.io/ears_dataset/)) dataset.  
The signal is stereophonic: here, the left channel is used as reference, and the STO is applied to the right channel only.

| Ideal | With Packet Loss (rate 10%) |
| :---: | :---: |
| <audio controls> <source src="./audio/69_stereo.mp3" type="audio/mpeg"> </audio> | <audio controls> <source src="./audio/69_pl.mp3" type="audio/mpeg"> </audio> |
