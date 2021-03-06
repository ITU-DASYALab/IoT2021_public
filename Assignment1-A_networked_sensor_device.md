# Assignment 1

## A networked sensor node

### Idea:

Monitoring of indoor climate is a relevant task, and more so in time of covid,
as the general room climate coorelates to some extent with aerosol concentrations.
CO2 (carbondioxide) concentrations are a good marker for indoor climate.

We draw some inspiration here from a widely popular german project, #Co2Ampel:
https://twitter.com/search?q=%23co2ampel

Most of the existing implementations are Arduino/C based, whereas we will work on

embedded python aka micropython.

The general goal is to measure, communicate and store

CO2 concentrations, Temperature and relative humidity.

You have wide freedom of choice as to how you achive this, e.g.

- which networking technology to use (it could be wired, wireless (Wi-Fi, sigfox, LoRa, bluetooth, ..)
- what additonal user interfaces you implement (local display? LEDs, sound, mobile app notifications, ..?)
- which data backend you choose

All these design choices will be tightly connected to things we talk about in the lectures,
and will require your active input -
come up with your idea and request support as needed!
We can create or open cloud instances, networks, 
we can procure additional gear, and so forth.
We can loan out LoRa gateways for home deployment.

Your are welcome to work on variations of this general idea,
e.g.
add outdoor components, additional or different sensors, etc


### Non-mandatory!

This assignment is not mandatory, but it is a great way to explore many of the aspects from class.
You can use this small device to get experience with some of the constraints that are inherent in IoT systems, like limited compute, power, bandwidth, cost, storage, etc.

The suggested voluntary hand-in for this assignment is a short report (5-10 pages) describing your system and which design choices you made. 
We encourage a clearly structured report and the use of system diagrams, flow-charts to describe the states of the system, graphs of experimental results/data, etc.

This is also an opportunity to discuss the limitations of your systems and how you would go about extending (e.g. for scaling out, making a battery-powered version, etc), and get feedback on these reflections.
The exam will cover many of these aspects, where you will be asked to discuss and give examples.
This assignment is highly suitable as preparation for the exam. You might even be able to use some of the text directly.

### Base kit

Your base kit will consist of:

pycom LoPy4 boards & accessories (expansion board, antenna, display, batteries (where needed), ...)
https://docs.pycom.io/datasheets/development/lopy4/

A sensirion SCD30
https://www.sensirion.com/en/environmental-sensors/carbon-dioxide-sensors/carbon-dioxide-sensors-co2/

### URLs

Here are some good starting points:

pycom general doc
https://docs.pycom.io/

LoPy4 pinout
https://docs.pycom.io/gitbook/assets/lopy4-pinout.pdf

SCD30 lib
https://github.com/agners/micropython-scd30

Display lib (optional)
https://github.com/mcauser/micropython-pcd8544

MQTT lib
https://github.com/pycom/pycom-libraries/blob/master/examples/mqtt/mqtt.py

I2C doc
https://docs.pycom.io/firmwareapi/pycom/machine/i2c/#app


