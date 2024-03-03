# Salt Lake City 3533.89 - 3534.11 MHz Multi-Transmitter Measurement Campaign

## Description
Please see https://docs.google.com/presentation/d/1uisWySmkMuHB8V5RjwVS0rMU_LtY-mD7X9nGiY8x1O0/edit?usp=sharing for details on transmission parameters, resulting power distributions, stationary and rotational fading analysis, and some research ideas.

## Json File
The JSON file is designed with a straightforward and efficient structure. At the highest level, the file is organized by timestamps, each key representing the precise moment of data collection, accurate to the second. Within each of these timestamp keys, there are two primary sub-keys: one for the core data and another for associated metadata.

The main data is stored under the key "pow_rx_tx", and it comprises five numerical values. These values, in order, represent:

1. Signal Power Indicator
2. Receiver Latitude
3. Receiver Longitude
4. Transmitter Latitude
5. Transmitter Longitude

The metadata section of the JSON file focuses on a singular piece of information associated with each timestamp. Specifically, it denotes the mode of data collection for the corresponding file, indicating whether the data was gathered while the collector was walking or driving.

## Citation
If you use this data in your research, please cite it:

```
@misc{tadikmeas2024,
    author       = "Tadik, S. and Singh, A. and Mitchell, F. and Hu, Y. and Yao, X. and Webb, K. and Sarbhai, A. and Maas, D. and Orange, A. and Van der Merwe, J. and Patwari, N. and Ji, M. and Kasera, Sneha K. and Bhaskara, A. and Durgin, Gregory D.",
    title        = "Salt Lake City 3534 MHz Multi-Transmitter Measurement Campaign",
    year         = "2024",
    month        = "March",
    howpublished = {\url{https://github.com/serhatadik/slc-3534MHz-meas}},

}
```
