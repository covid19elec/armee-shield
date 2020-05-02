# A.R.M.E.E shield

Electronic shield for A.R.M.E.E emergency respirator for use in COVID-19 patients

## Overview

ARMEE shield is a pluggable extension built on top of A.R.M.E.E pneumatic oscillator.

## Goals

- **Availability** : Open source for everybody to reproduce and manufacture
- **Therapeutic** : Shield must be helpful to treat sedated COVID-19 patients in need of mechanical ventilation
- **Mass production** : Daily production in the order of thousand units by day
- **Modularity** : Pluggable interfaces to support the following requirements
  * Device must be easily attached detached on top of an A.R.M.E.E pnaumatic oscillator
  * Other devices and accessories should be easily connected to the shield
- **Interoperbility** : Device should be plugged in to one of many available devices, including
  * Monitors, by offering an open monitoring API and implementing popular standards
  * Drives, it should be possible to connect one of multiple alternatives to air intake (at least one mechanical and pneumatic variant is compulsory)
  * Standard general purpose (Prometheusi, Grafana, ...) dashboard software and medical user display/ control panels
- **Customizability** : Product design should adapt to alternate configurations and scenarios including
  * mechanical solution should fit in the multiple usage scenarios of the device
  * product should be manufactured using a variety of electronic components according to availability
- **Dynamic operation mode** Actuators to change oscillaor parameters
  * HMI to configure set point of ARMEE variables
  * HMI to configure set point of other devices connected to the shield
  * software must be consistent with HMI settings and must support multiple configurations

