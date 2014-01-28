The Arduino HAWAII - Home Automation Web And Invocation Interface

Created by: Frank Robin Danielsen
License: TBD

Credits



-----------------------------
HAWAII is a home automation system that is accessible through http requests. Locally the system communicates using XBee radios

The Control unit is responsible for communication with the end devices. Communication is in the form of receiving data and invoking actions on the end devics.

The end devices will implement certain functions reflecting their onboard sensors and actuators. Upon joining the network the end device will provide a list of the onboard sensors and actuators. It will also provide a list of the standard functions implemented (as dictated by the Control unit).

