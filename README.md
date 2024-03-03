# 3534 MHz Narrowband Measurement Campaign

## Description
The dataset for 3534 MHz narrowband measurement campaign in json format. Please see https://docs.google.com/presentation/d/1uisWySmkMuHB8V5RjwVS0rMU_LtY-mD7X9nGiY8x1O0/edit?usp=sharing for details on transmission parameters, resulting power distributions, staionary and rotational fading analysis, and some research ideas.

## Json File
The JSON file is designed with a straightforward and efficient structure. At the highest level, the file is organized by timestamps, each key representing the precise moment of data collection, accurate to the second. Within each of these timestamp keys, there are two primary sub-keys: one for the core data and another for associated metadata.

The main data is stored under the key "pow_rx_tx", and it comprises five numerical values. These values, in order, represent:

1. Signal Power Indicator
2. Receiver Latitude
3. Receiver Longitude
4. Transmitter Latitude
5. Transmitter Longitude

The metadata section of the JSON file focuses on a singular piece of information associated with each timestamp. Specifically, it denotes the mode of data collection for the corresponding file, indicating whether the data was gathered while the collector was walking or driving.
