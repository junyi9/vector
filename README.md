# vector
Document for the vehicle testbed learning and programming with raspberry pi

## Installation of Raspberry Pi OS

- [Download Raspberry Pi Imager](https://downloads.raspberrypi.org/imager/imager_latest.dmg)
- Have a microSD card ready (8GB or larger)

Compiling ROS takes 45 minutes or more.

Upgrade the system dependencies:
```bash
sudo apt update
```

- Add your device to the vu-devices for wifi connection [link to regeister](https://device-registration.app.vanderbilt.edu/guest/mac_list.php)

Our system OS version:
- Ubuntu 22.04 LTS - Debian 23 bookworm 2025 release.

## Install git
```bash
sudo apt install git
```

## Install from LibPanda
```bash
git clone https://github.com/jmscslgroup/libpanda
```

Follow the instructions in the `libpanda` repository `README.md` to install the library.

## Install cmake
```bash
sudo apt install cmake
```

## Install ROS 1


## LibPandaApps

## strym

`strym` is a library for analysis.


## Notes

`libpanda` is just keeping it as it is.

To change the yaml in libpanda to select the correct can_to_ros specification.

### ROS nodes

- `custom_ros_node` do the traffic logic. It's what i need to work on.

- `can_to_ros` is what we need to modify to facilitate our own use cases.

- `live-tracker` is a ros node.

any simulink ROS nodes

The changes should be made on the server side and the ROS node side.