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


|  Static Infrastructure | Sensor  |  Collected Data | Shared Data |
|---|---|---|---|
|  | 12 UWB Pozyx  |  - | <a href="https://eostore.itc.utwente.nl:5001/sharing/1gJRLdQ71"></a>reference positions|
|  | LiDAR: Velodyne VLP16 | raw profiles | <a href="https://eostore.itc.utwente.nl:5001/sharing/c4LlTkVjT"></a>raw profiles with timestamp|
|  Agents | Onboard sensor  |  Collected Data | Shared Data |
| UAS1 - DJI Phantom 4Pro RTK | UWB: Pozyx <br> embedded GNSS <br> embedded camera | ranges <br> positions <br> images | ranges wrt static and moving agents <br> reference trajectory <br> images |
| UAS2 - DJI Phantom 4Pro | | | |
| UAS3 - DJI Phantom 4Pro | | | |
| UAS4 - DJI Matrice 210 | | | |
| CAR0 - GPSVan | | | |
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

