# Gazepoint Eye Tracker


## Content
* [Where To Find](#where-to-find)
* [In The Box](#in-the-box)
* [How To Make It Works](#how-to-make-it-works)
  * [Assembly](#assembly)
  * [Charging The Batteries](#charging-the-batteries)
  * [Powering Up](#powering-up)
* [Device's Functionalities and Features](#devices-functionalities-and-features)
* [Safety Guidelines](#safety-guidelines)
  * [Environmental Consideration](#environmental-consideration)
  * [Operation](#operation)
  * [Pre-Flight Checklist](pre-flight-checklist)
* [SDK](#sdk)
* [Accessories](#accessories)
  * [DJI Goggles](https://github.com/SERLatBTH/DJIGoggles)
  * [Mavic 2 Fly More Kit](#mavic-2-fly-more-kit)
  * [Backpack](#backpack)
* [Putting The Device Back](#putting-the-device-back)
* [More Documentations](more-documentations)


## SDK

* The required SDK and API are packaged with [Gazepoint software](https://www.gazept.com/downloads/), no additional installation is required.

### API
+ A key requirement of the API is that it does not require any DLL’s, libraries, or any programming language or platform specific components.
+ The API uses a standard TCP/IP socket for communication between a client (the application) and the server (the source of eye-tracking data).
+ The data format uses the extensible markup language (XML) to format the data transmit between the client and server.
+ Since both TCP/IP and XML are open standards, they can be readily implemented in any language or operating system.

For a complete API reference go to the [link](https://www.gazept.com/dl/Gazepoint_API_v2.0.pdf).

### eye-tracker-api
+ [eye-tracker-api](https://github.com/njss/eye-tracker-api) is a generic Java API to interface with various eye tracking systems. An API written in Java for establishing connections, configuring, calibrating, and receiving data from various eye tracking systems. Currently supported and tested systems include SMI iViewX RED250 and ITU GazeTracker.
+ The goal of this project is to provide a common software interface to eye tracking systems and promote the establishment of a standard gaze data format.

### PyOpenGaze
+ [PyOpenGaze](https://github.com/esdalmaijer/PyOpenGaze) is a python library or a wrapper for GazePoint's OpenGaze API (version 2.0).
+ It should be compatible with all eye trackers that work through the OpenGaze API. This includes the GazePoint GP3.

### Examples and Tools
+ [PyGaze](https://www.pygaze.org/)
+ [Gazepoint Heat Map](https://github.com/TobiasRoeddiger/GazePointHeatMap)
+ [Gazepoint 2 Json](https://github.com/MLHale/Gazepoint2Json)
+ [Gazepoint Matlab Toolbox](https://github.com/RingoHHuang/gazepoint-matlab-toolbox)
