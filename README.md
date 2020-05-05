# A.R.M.E.E shield

Extension shields for A.R.M.E.E emergency respirator for possible use in COVID-19 patients

![License](https://img.shields.io/github/license/covid19elec/armee-shield)

## Overview

ARMEE shield is a pluggable extension built on top of A.R.M.E.E pneumatic oscillator.

## Goals

- **Availability** : Open source for everybody to reproduce and manufacture
- **Therapeutic** : Shield must be helpful to treat sedated COVID-19 patients in need of mechanical ventilation
- **Mass production** : Manufacturability in the order of thousand units and focus on different tools
  * CNC
  * High-pressure die casting (HPDC) mold
  * SLA, SLS or Polyjet printers
  * Injection molds
  * Machining/milling, or any other precision forming
  * FDM (Fused Deposition Modelling)
- **Modularity** : Pluggable hardware interfaces to support the following requirements
  * Device must be easily attached / detached on top of an A.R.M.E.E pneumatic oscillator
  * Other devices and accessories should be easily connected to the shield
- **Interoperbility** : Device should be plugged in to one of many available devices, including
  * Monitors, by offering an open monitoring API and implementing popular standards
  * Drives, it should be possible to connect one of multiple alternatives to air intake (at least one mechanical and pneumatic variant is compulsory)
  * Standard general purpose (Prometheusi, Grafana, ...) dashboard software and medical user display/ control panels
- **Customizability** : Product design should adapt to alternate configurations and scenarios including
  * mechanical solution should fit in the multiple usage scenarios of the device
  * product should be manufactured using a variety of electronic components according to availability
- **Dynamic operation mode** Actuators to change oscillator parameters
  * HMI to configure set point of ARMEE variables
  * HMI to configure set point of other devices connected to the shield
  * software must be consistent with HMI settings and must support multiple configurations
- **Detachable** It should be possible to detach shield for oscillator to operate in standalone manual mode
  * ... which means that shield may be used as some sort of portable calibration tool

## References

- A.R.M.E.E project
  * [Web site](http://www.armeevent.com/)
  * [Github repository](https://github.com/MillionVentilators/ARMEE_Ventilator_1.0)
  * [Design documentation v. 1.0](https://docs.google.com/document/d/1ZnPGnA-GKtFLsJEDVVLLKqNAKSk3q6F47YqvtuoJVXw/)
- J.W. Joyce, Jr. ["TM 68-30 The Army Emergency Respirator"](https://github.com/cubanmakers/ARMEE_Ventilator_1.0/blob/master/research/1968_Army_Emergency_Respirator.pdf). Harry Diamond Labs, US Army Materiel Command, 1968
- J.I. Lee, A. Saied, G.M. Thomson, US 2019 247 599A1, ["Low Flow Percussive Respiratory Apparatus And Related Treatment"](https://patentswarm.com/patents/US20190247599A1)




