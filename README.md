# CONTEST dataset
# Collaborative pOsitioning and NavigaTion bEtween ground and uaS plaTforms
_________________________________________________________________________
GNSS allows positioning and navigation of ground and aerial platforms/agets almost everywhere and has been widely used in a large variety of devices and applications.

But, despite developments in hardware technologies and Radio-Frequency (RF) signal processing, GNSS cannot be fully available or reliable in certain environments (e.g. dense forestry, tunnels, urban canyons, etc.) or when RF interference is present (e.g. spoofing or jamming).

Therefore, alternative positioning approaches were studied, including collaborative navigation, where platforms navigating in close vicinity can share position and navigation information (vehicle-to-infrastructure - V2I and vehicle-to-vehicle - V2V communications) and a joint navigation solution can potentially provide better results for all platforms with respect to individual ones.
<p><img src="contest.png"><p>
The CONTEST dataset wants to provide multiple data streams to test <b>collaborative positioning</b> approaches, involving both terrestrial and aerial (Unmanned Aerial Systems / Vehicles) platforms, and using several sensors, such as Ultra-Wide Band (UWB) transceivers, cameras, LiDARs, GNSS. The CONTEST data can therefore support the development, testing and comparison of individual or integrated use of imaging data, LiDAR and UWB ranging for collaborative positioning and navigation purposes. This includes the possibility to execute and validate visual and LiDAR odometry or SLAM approaches, hybrid adjustment, UWB trilateration algorithms, etc. To ensure reliable validation results, accurate GNSS-based reference solutions are provided for all the platforms.

The CONTEST dataset is joint work bewtween the University of Florence (Italy), The Ohio State University (USA) and Bruno Kessler Foundation - FBK (Italy).
_________________________________________________________________________

In the following table, the collected and share data are listed (TO BE COMPLETED). 


|  <p align="center"><strong> Static Infrastructure <p align="center"><strong> | <p align="center"><strong> Sensor <p align="center"><strong> | <p align="center"><strong> Collected Data <p align="center"><strong> | <p align="center"><strong> Shared Data <p align="center"><strong> |
|---|---|---|---|
|  | 12 UWB Pozyx  |  - | <a href="https://eostore.itc.utwente.nl:5001/sharing/1gJRLdQ71"></a>reference positions|
|  | LiDAR: Velodyne VLP16 | raw profiles | <a href="https://eostore.itc.utwente.nl:5001/sharing/c4LlTkVjT"></a>raw profiles with timestamp|
|  <p align="center"><strong> Agents <p align="center"><strong> | <p align="center"><strong> Onboard sensor <p align="center"><strong>  |  <p align="center"><strong> Collected Data <p align="center"><strong> | <p align="center"><strong> Shared Data <p align="center"><strong> |
| UAS1 | UWB: Pozyx      | ranges    | ranges wrt static and moving agents |
| UAS1 | embedded GNSS   | positions | reference trajectory                |
| UAS1 | embedded camera | images    | images                              |
| UAS2 | UWB: Pozyx      | ranges    | ranges wrt static and moving agents |
| UAS2 | GNSS: Emlid M2  | positions | reference trajectory                |
| UAS2 | embedded camera | images    | images                              |
| UAS3 | UWB: Pozyx      | ranges         | ranges wrt static and moving agents |
| UAS3 | GNSS: Emlid M2  | positions      | reference trajectory                |
| UAS3 | embedded camera | images, videos | images, videos                      |
| UAS4 | UWB: Pozyx          | ranges         | ranges wrt static and moving agents |
| UAS4 | embedded GNSS       | positions      | reference trajectory                |
| UAS4 | Camera: DJI FC6310S | images, videos | images, videos                      |
| CAR0 | UWB: Pozyx                          | ranges        | ranges wrt static and moving agents                               |
| CAR0 | GNSS: Leica GS25, Septentrio PolRx5 | positions     | reference trajectory from GNSS and IMU integration and correction |
| CAR0 | IMU: Honeywell H764G                | inertial info | reference trajectory from GNSS and IMU integration and correction |
| CAR0 | LiDAR Velodyne VLP16                | raw profiles  | raw profiles with timestamp                                       |

| CAR1 | UWB: Pozyx                             | ranges        | ranges wrt static and moving agents                               |
| CAR1 | GNSS: Topcon Hyper VR, Novatel PwrPak7 | positions     | reference trajectory from GNSS and IMU integration and correction |
| CAR1 | IMU: SPAN-IGM-S1                       | inertial info | reference trajectory from GNSS and IMU integration and correction |
| CAR1 | LiDAR Velodyne VLP16                   | raw profiles  | raw profiles with timestamp                                       |
| CAR1 | Camera: Sony Alpha 6000                | video         | video                                                             |




| CAR0 | Camera: Sony Alpha 6000             | video         | ranges wrt static and moving agents <br> reference trajectory from GNSS and IMU integration and correction <br> raw profiles with timestamp <br> video |
| CAR1 - Honda CRV | | | |
| CAR2 - Honda Pilot | | | |
| CAR3 - CyberCar | | | |
| Pedestrian1 | | | |
| Pedestrian2 | | | |
| Cyclist1 | | | |
| Cyclist2 | | | |
| Static LiDAR | | | |

_________________________________________________________________________
### Credits
The CONTEST dataset is publicly available for research purposes.<br>
If you use this dataset for your research, please cite the data source (https://github.com/3DOM-FBK/Collaborative_Navigation). A scientific pubblication is in preparation. 

_________________________________________________________________________
### License
The data provided here is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
