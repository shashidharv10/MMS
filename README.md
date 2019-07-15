# MMS
Motorbike Management System

This is an IoT project aimed at analysing the vitals of a motorbike.
It displays :
- the current fuel level.
- the battery level.
- the pressure in the tyres.
- smoke detector.
- an alert if the bike is being moved despite having the locks and other securities in place.

The sensors include a MQ2 smoke detector, a tilt switch , a barometric pressure indicator, an electronic potentiometer and a fluid level indicator.
The fluid level resistor is corrosion reistant and can endure the fossil fuel corrosion. The level is measured and the length of the indicator measured is converted into the volume by taking density into account.
The smoke detector is used to identify if there is any problem with the engine exhaust.
The barometric pressure always maintains a constant check on the air pressure and alerts if any loss in pressure indicating that there has been a leak.
The tilt switch is designed to maintain static equilibrium in the switch. If the equilibrium shifts because of some changes then the switch is turned on. This alerts the user that the vehicle has been moved.

All the data from the sensor is relayed to the device using the bluetooth module.
All the sensors are controlled using a Arduino and Node MCU.
The Node MCU is again used to send a message to the user incase of an emergency (example if the bike is moved away).
