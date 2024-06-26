## GDP Group 49 2023/24 - Drone Dock 👋

**Integration of Drone and Rover**: *Integration of a Drone with a Ground Rover for Navigation and Docking*

![HANGAR-1](https://github.com/DroneDock/.github/assets/107824428/a65199ec-7862-45a8-b043-faa6115b1660)

HANGAR-1 is a state-of-the-art vision-based tracking system that allows the platform to track the movement of the drone in real time. It boasts 3-DOFs, with a 360 degree rotation, 20 cm extension and can tolerate up to 80 degrees of inclination.

![VID-20240604-WA0006_1](https://github.com/DroneDock/.github/assets/107824428/8e47c2fa-bfc7-437b-ba94-880b00142e71)
![Action 1_1](https://github.com/DroneDock/.github/assets/107824428/90efbf2a-5294-4f4e-bdee-19361059d200)
![Bottom Rotation_1](https://github.com/DroneDock/.github/assets/107824428/2d531c6e-0ae1-4a6f-8466-71aee6231ee8)

The repositories in this organisation are:
* **submissions**: This repository contains the final project deliverables: report, presentation and video.
* **platform-control**: The main repository containing the codes to control the platform.
* **aruco-RaspberryPi**: This repository contains the code needed to run codes pertaining the ArUco marker, including calibration, detection and pose estimation for the Raspberry Pi controller.
* **aruco-JetsonNano**: (Deprecated) This repository contains the code needed to run codes pertaining the ArUco marker, including calibration, detection and pose estimation for the Jetson Nano controller. *This is deprecated - the Jetson Nano is not used due to the lack of support of PWM pins.*
* **drone_sim_setup**: This repository contains the documentation related to setting up the drone simulation stack, including ArduPilot, ArduPilot SITL, Gazebo, Ubuntu and WSL.
* **drone_setup*: This repository contains a word document to calibrate the drone and the ArduPilot firmware.
* **cad_files**: This repository contains all the CAD files needed to manufacture the docking platform, and a word document of how to assemble it.
