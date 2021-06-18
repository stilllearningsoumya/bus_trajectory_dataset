# Bus Trajectory Dataset
This dataset contains the bus trajectory dataset collected by 6 volunteers who were asked to travel across the sub-urban city of Durgapur, India, on intra-city buses (route name: 54 Feet). During the travel the volunteers captured sensor logs through an Android application installed on COTS smartphones. The details of the modalities logged by the Android application is given as follows.

<p align="center">
      <img src="route_54_feet.PNG" width="70%"/>
</p>

## Available Modalities

|    `Modality`       | `Sample Rate (Hz)` |      `File Pattern`       |
|:--------------------|:------------------:|:-------------------------:|
|    GPS              |        1           |All/Bus_GPS_\*.txt         |
|    Speed            |        1           |All/Bus_GPS_\*.txt         |
|    Altitude         |        1           |All/Bus_GPS_\*.txt         |
|    accelerometer    |        197         |All/Bus_ACC_\*.txt         |
|    Gyroscope        |        197         |All/Bus_GYR\*.txt          |
|    WiFi             |        8000        |All/Bus_WiFi_\*.txt        |
|    Light            |        5           |Light/Bus_LIGHT\*.txt      |
|    Sound            |        8000        |Sound/Bus_SOUND_\*.wav     |


## Known Issues with the Dataset
Some of the minor known probelms in the dataset are:
1. Some of the WiFi SSID(s) have characters replaced by unrecognised characters (or even emojis).
2. A suggested way of calculating the speed of the vehicle is by computing the difference in distance from the GPS coordinates and then checking the time taken to travel that distance. However, that would also include the stoppage time, if any.

## Dataset Link
[Download the dataset from here](https://drive.google.com/file/d/1uvFCq4wXkjVo8YBDYBu-tYcXe1DDLSIH/view?usp=sharing)

# Reference
To refer this dataset, please cite the following work.

[Download the paper from here](https://dl.acm.org/doi/abs/10.1145/3397536.3422273).

BibTex Reference:
```
@inproceedings{10.1145/3397536.3422273,
author = {Mandal, Ratna and Karmakar, Prasenjit and Roy, Abhijit and Saha, Arpan and Chatterjee, Soumyajit and Chakraborty, Sandip and Saha, Sujoy and Nandi, Subrata},
title = {Ad-HocBusPoI: Context Analysis of Ad-Hoc Stay-Locations from Intra-City Bus Mobility and Smartphone Crowdsensing},
year = {2020},
isbn = {9781450380195},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3397536.3422273},
doi = {10.1145/3397536.3422273},
abstract = {Public city bus services across various developing cities inhabit multiple stay-locations on the routes due to ad-hoc bus stops to provide on-demand passenger boarding and alighting services. Characterizing these stay-locations is essential to correctly develop models for bus transit patterns used in various digital navigation services. In this poster, we create a deep learning-driven methodology to characterize ad-hoc stay-locations over bus routes based on crowd-sensing contextual information. Experiments over 720km of bus travel data in a semi-urban city in India indicate promising results from the model in terms of good detection accuracy.},
booktitle = {Proceedings of the 28th International Conference on Advances in Geographic Information Systems},
pages = {457–460},
numpages = {4},
keywords = {Crowdsensing, Bus Stay Locations, Smartphone sensor},
location = {Seattle, WA, USA},
series = {SIGSPATIAL '20}
}
```
For questions and general feedback, contact Sujoy Saha (sujoy.saha@cse.nitdgp.ac.in).
