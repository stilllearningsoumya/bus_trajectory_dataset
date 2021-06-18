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

[Download the paper from here](https://arxiv.org/abs/2105.13131).

BibTex Reference:
```
@misc{mandal2021exploiting,
      title={Exploiting Multi-modal Contextual Sensing for City-bus's Stay Location Characterization: Towards Sub-60 Seconds Accurate Arrival Time Prediction}, 
      author={Ratna Mandal and Prasenjit Karmakar and Soumyajit Chatterjee and Debaleen Das Spandan and Shouvit Pradhan and Sujoy Saha and Sandip Chakraborty and Subrata Nandi},
      year={2021},
      eprint={2105.13131},
      archivePrefix={arXiv},
      primaryClass={cs.LG}
}
```
For questions and general feedback, contact Sujoy Saha (sujoy.saha@cse.nitdgp.ac.in).
