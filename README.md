<p align="center">
      <img src="route_54_feet.PNG" width="100%">
      </p>
# Bus Trajectory Dataset
This dataset contains the bus trajectory dataset collected by 6 volunteers who were asked to travel across the sub-urban city of Durgapur, India, on intra-city buses (route name: 54 Feet). During the travel the volunteers captured sensor logs through an Android application installed on COTS smartphones. The details of the modalities logged by the Android application is given as follows.

## Available Modalities
|    `Modality`       | `Sample Rate (Hz)` |            `Unit`         |      `File Pattern`              |
|:--------------------|:------------------:|:-------------------------:|:---------------------------------|
|    GPS              |        1           |            -              |       All/Bus_GPS_\*.txt         |
|    Speed            |        1           |            m/s            |       All/Bus_GPS_\*.txt         |
|    Altitude         |        1           |            m              |       All/Bus_GPS_\*.txt         |
|    accelerometer    |        197         |            m/s<sup>2</sup>|       All/Bus_ACC_\*.txt         |
|    Gyroscope        |        197         |            rad/s          |       All/Bus_GYR\*.txt          |
|    WiFi             |        8000        |            -              |       All/Bus_WiFi_\*.txt        |
|    Light            |        5           |            lux            |       Light/Bus_LIGHT\*.txt      |
|    Sound            |        8000        |            dB             |       Sound/Bus_SOUND_\*.wav     |

## Known Problems in the Dataset

## Dataset Link
[Download the dataset from here](https://drive.google.com/file/d/1uvFCq4wXkjVo8YBDYBu-tYcXe1DDLSIH/view?usp=sharing)
## Dataset Pre-processing
Codes to pre-process the dataset will be available soon.
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
