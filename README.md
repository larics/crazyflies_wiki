# crazyflies_wiki

This wiki serves as a source of information about crazyflies bundle we use in LARICS Laboratory to students and researchers. It contains overview of students' projects with crazyflies and instructions on how to use the belonging equipment in the lab alongside the:  
* [docker](https://github.com/larics/docker_files/tree/master/ros2/ros2-humble/crazyflies-sitl) with CrazySim SITL and crazyswarm2 ROS2 package. Ubuntu 22.04. and ROS2 Humble based with ros1 bridge option
* [docker](https://github.com/larics/docker_files/tree/master/ros2/ros2-jazzy/crazyflies) with the latest crazyflies-firmware, cfclient and crazyswarm2 ROS2 package to communicate with or to deploy your code on the real crazyflies. Ubuntu 24.04. and ROS2 Jazzy based

Wiki serves da ne zamijeni skroz izvore informacija već da okupi na jednom mjestu sve probleme koje smo imali, kako ih se riješilo, lakše snalaženje i preusmjeravanje na druge značajne izvore. If there are any problems regarding info on this page, some mistakes are made, or just want to offer a solution to some problems, please open an issue or start a discussion. If you are too shy, you can send an e-mail to marijana.peti@fer.hr. :) 

# students' projects: 
* Formation changes (choreography) in different localization systems: loco positioning and optitrack [video](link to video)
* Consensus based formation control (Multi Robot Systems course - project) [video](link to video)
* Inspection trajectory for a small UAV [video](link to video)
* Navigation of the UAV in 3D space using semantics [video-simulation](link to video), [video-experiments](link to video)

# simulation:
To develop the code, it is first recommended to use the simulation docker. It is based on the CrazySim Software in the Loop Simulator integrated with Gazebo physics engine and sensors. The basic instruction on CrazySim can be found [here](link). If a user wants to develop code in ROS2 based package it is possible by using [crazywarm2](link) package. Detailed instructions on crazyflies can be found [here](link). Also the detailed setup of the docker can be found in the readme (link to readme).

# hardware:
To further deploy your code on crazyflies, you can use docker setup with the latest firmware. The detailed instructions are given in the readme (link to readme). 

**Equipments list:**
|![crazyflie_2 1_585px](https://github.com/user-attachments/assets/f5682ac9-13ad-4d07-87f1-e7fb2cfecd29)||![CR 2 0-dongle- 585px](https://github.com/user-attachments/assets/e676a21a-456b-4c10-83ea-bccb4a72068a)|
| :-: | - | :-: |
| 10 x Crazyflies 2.1. |  | 10 x Crazyradio 2.0. |


Decks: 
|![ai-deck-side-585px](https://github.com/user-attachments/assets/d0b2d148-876b-401a-af44-59ff228d1e71)||![multi-ranger_deck_585px-1](https://github.com/user-attachments/assets/2bc84a87-7ac7-435b-ba12-60a2a69e990c)||![flow_deck_v2_585px](https://github.com/user-attachments/assets/83a3441b-4491-4314-9cb8-73319bf42b3c)||![ledring-side](https://github.com/user-attachments/assets/da3eec92-181a-4503-99dd-77bfeb2be4e3)||![mocap_marker_deck_585px](https://github.com/user-attachments/assets/19cb3a41-d8e0-4104-a383-c7fce4d29703)|
| :-: | - | :-: | - | :-: |-| :-: |-| :-: |
| 5 x AI Deck |  | 5 x Multi ranger deck | | 10x Flow deck | |5x LED deck| | 7 x Optitrack marker deck|

Adds on: 
|![Screenshot from 2025-01-03 09-56-26](https://github.com/user-attachments/assets/a6309ebb-ab1a-48f3-bf46-41be3849bd48)|| ![Screenshot from 2025-01-03 09-56-43](https://github.com/user-attachments/assets/66321f3d-57a6-4ff6-91a3-356e208c3f44)|| ![reflective-marker-kit-65mm](https://github.com/user-attachments/assets/05cf544a-3337-419a-99f1-8e690531322c)|| ![Charger-585px](https://github.com/user-attachments/assets/8a6179a2-ebe8-40df-9e48-c0e9f228c358)||![250mah-lipo-battery](https://github.com/user-attachments/assets/ac9c58a7-5a5f-4690-9b95-df0542e14457)|
| :-: | - | :-: | - | :-: |-| :-: |-| :-: |
| 5 x Grayscale camera module |  | 2 x Color camera module  | | 20 x reflective markers 6.5 mm  | |10 x Chargers| | 30 x 250mAh batteries|

Loco positioning system: 
|![locoPositioning_node_585px_side](https://github.com/user-attachments/assets/cd2764cb-9408-4b7b-b57b-d952e68b27a3)||![locoPositioning_deck_585px_side](https://github.com/user-attachments/assets/f87c6b5c-cf46-4919-b5bc-3194baba453f)||![veger-a10-powerbank-10000-mah-crn-1](https://github.com/user-attachments/assets/7663b9c2-790d-43ac-b27b-0b94b8e09ea6)||![WhatsApp Image 2025-02-24 at 16 42 45](https://github.com/user-attachments/assets/ec48ce29-da7a-4f77-adfe-a2140eb5e8b6)||![uusbhaub3m main](https://github.com/user-attachments/assets/bfc31a06-9516-4a7f-a441-2fcee68e0a34)|
| :-: | - | :-: | - | :-: |-| :-: |-| :-: |
| 8 x Loco positioning node (LPN) |  | 10 x Loco positioning deck (LPD) | | 16x 10000mAh power banks for loco positining nodes  | |10x 3D printed holders for LPN| | 8x 3m mini-USB to USB Cables|
* you need  the 4x tripods

Equipment for transferable optitrack arena:
|![images](https://github.com/user-attachments/assets/d632b541-b44b-470d-b412-8c321890e185)||![cullmann-flexx-tabletop-set-komplet-cros-4007134420601_1](https://github.com/user-attachments/assets/48150a0d-dc89-434c-9fb0-4dfd578d5f0d)||![standFloor](https://github.com/user-attachments/assets/daecc4f0-d363-4129-b76c-9e8f02b1be12)||<ul><li>POE switch</li><li>router</li><li>USB optitrack key</li><li>long ethernet cables</li></ul>|
| :-: | - | :-: | - | :-: |- | :-: |
| Min 4x Optitrack cameras |  | Min 4x Optitrack camera holders | | Min 4x tripods  |

Spare parts
|![propellers-47-17-black-1024px](https://github.com/user-attachments/assets/48bbc513-5c98-4c06-b43f-79e378954b8c)||![4-x-7-mm-dc-motor-pack-for-crazyflie-2x](https://github.com/user-attachments/assets/e59019b1-2144-448e-9a1c-b716a35d7790)||![4-spare-crazyflie-motor-mounts-7-mm](https://github.com/user-attachments/assets/68743516-2af6-4275-9bd5-3e278fb76c1c)|
| :-: | - | :-: | - | :-: |
| Propellers (small R is for the counterclockwise direction)|  | Motors | | Motor mounts |

- dodati linkove
- flashing the dongle, usb permissions
## Starting with crazyflies 

### Crazyflies dongle
Crazyflies communicate with a computer using Crazyradio (radio dongle) that works on 2.4 GHz. One dongle can communicate with several Crazyflies simultaneously. When using the dongle for the first time, you need to [flash](https://www.bitcraze.io/documentation/tutorials/getting-started-with-crazyradio-2-0/#enter-bootloader-mode) it. This is only required if the dongle is taken straight out of the box for the first time. 

### cfclient
Crazyflie client (`cfclient`) is the default UI for controlling the Crazyflie, flashing firmware, setting parameters and logging data. For more info check this [link](https://www.bitcraze.io/documentation/repository/crazyflie-clients-python/master/userguides/userguide_client/). The crazyflie client can be started by typing the command: `cfclient` or `python3 -m cfclient.gui`.  It can be used to change the address of a crazyflie, check the battery status, update firmware...

#### Changing the address
To change the address of a crazyflie, follow the instructions [here](https://www.bitcraze.io/documentation/repository/crazyflie-clients-python/master/userguides/userguide_client/#firmware-configuration). It is recommended to use 2Mbit/s radio bandwidth, and if using different channels, they should be 2 channels apart at least . If two crazyflies are on the same channel they should have different radio address. Since crazyradio is working on the 2.4 GHz, the same as the wi-fi, there fore it is recommended to set the radio channel to 90 and above, in order to avoid interference with wi-fi.

#### Joystick control
After starting the cfclient and connecting to one of the crazyflies you can setup the joystick following the instructions on this [link](https://www.bitcraze.io/documentation/repository/crazyflie-clients-python/master/userguides/userguide_client/#input-devices). Crazyflies can be controlled with joystick without any deck on it, however it cannot hold the height and hover. It is better to add optical flow deck this will enable holding the altitude (hovering) and the assist mode dropdown menu in the cfclient should be set to `Hover`. 

![Crazyflies-cfclient](https://github.com/user-attachments/assets/5d9fbad4-358a-4dc5-81d1-60db4d814f49)

One of the example mappings for a joystick is shown in the image below:
![Crazyflies - joystick control](https://github.com/user-attachments/assets/8a79888e-8bbe-4c84-a057-2b13d5e96ae1)

For a crazyflies with optical flow to hover, the assisted mode button should be pressed during the flight, in order to hold the altitude. 
### Charging crazyflies
Crazyflies have attached a small 250 mAh battery. Usually, with a full battery, the UAV has a flight time of approx. 7 minutes. However, this time can significantly reduce if there are additional decks on it. The full battery is around 4.1 V, and you shouldn't start flying if it falls below 3.7 V. These voltages are measured when the UAV is landed, during the flight it is normal that voltage drops up to 3.2. If it falls below 3.1V please land the UAV and replace the battery. You can check the battery in `cfclient`. Batteries can be charged while they are plugged in the crazyflies, by connecting the crazyflies to laptop with USB-microUSB and the crazyflie should be on. You can also replace the batteries, connect the empty ones to the charger. This way you can charge multiple batteries in paralel by connecting the charges in the USB-hub.

## Setting up and working with positioning systems
It is possible to fly in different localization systems with crazyflies. The detailed overview of positioning systems is [here](https://www.bitcraze.io/documentation/system/positioning/)
### Optical flow deck
With only using optical flow deck on crazyflies, it is possible to fly and hover without using external anchors. This deck installs on the bottom of the crazyflies and uses camera module that use ground texture and visible features to determine ground velocity of the ccrazyflie. Additinally, it has ToF ranging sensor that measures the distance to the ground. 
There are couple of things that need to be careful about when using this deck, and they are explained [here](https://www.bitcraze.io/documentation/tutorials/getting-started-with-flow-deck/#measurement-details) and [here](https://www.bitcraze.io/2023/11/go-with-the-flow-relative-positioning-with-the-flow-deck/). Also keep in mind that it is expected to fly over the flat floor, otherwise, because of the distance sensor the UAV might fluctuate and become unstable. 

### Loco positioning 
The Loco positioning system is a positioning system based on Ultra Wide Band (UWB) radio frequencies. It is used to find the absolute 3D position in the space. It consists of a set of anchors (Loco poitioning nodes) positioned in the room whose locations should be known. The other part is the Loco positioning deck that is attached to the crazyflies. You can check more information on this [link](https://www.bitcraze.io/documentation/system/positioning/loco-positioning-system/). Loco positioniing nodes are powered by power banks and should be set in the desired places. There are several modes of operation, and the recommended one is TDoA 3.  . You can check it by running `cfclient` and connecting to the UAV that has a Loco positioning deck. A detailed explanation is given [here](https://www.bitcraze.io/documentation/tutorials/getting-started-with-loco-positioning-system/). In the image below is an example of a setup we have in Ericsson with 8 anchors.

![loco_anchor](https://github.com/user-attachments/assets/572e6334-c53f-4a6f-8385-c7bae0f2e055)

- reconfiguring red ones in cf client and optical flow
- upis pozicija manual

### Optitrack
Optitrack is one of the motion capture systems, which uses IR cameras to detect the markers attached to the object that is tracked.
- what it is
- computer, IP, setup... single marker
- 




## Adding other decks
### AI deck - jlink, change the access point
### multi ranging deck
### LED deck


# Crazyswarm2
# Troubleshooting:
