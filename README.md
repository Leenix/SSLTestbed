# StreetFighter - Smart Streetlight Testbed
[![Build badge](https://travis-ci.org/Leenix/StreetFighter_Sensor_Testbed.svg?branch=master)](https://travis-ci.org/Leenix/StreetFighter_Sensor_Testbed)
[![Arduino badge](https://img.shields.io/badge/platform-Arduino-brightgreen.svg)](http://www.arduino.cc/)
[![License](http://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.en.html)

# What is it?
StreetFighter is a smart cities sensor platform intended for mounting inside LED street lights. The platform includes sensors to monitor road usage, and can manage street light dimming to adapt the light level to real-time traffic.

![Streetfighter installed in LED streetlight](https://github.com/Leenix/StreetFighter_Sensor_Testbed/wiki/images/pole.jpg)

## Why the stupid name?
- The main hardware platform of this project is the Arduino **Yun**.
- **Yun** (Lee) is a character from CAPCOM's **Street Fighter** franchise.
- Our sensor platform is intended for road-side deployment in **street** lights to **fight** energy waste
- It made sense to me...

# [Quick Start](https://github.com/Leenix/StreetFighter_Sensor_Testbed/wiki/Hardware-Installation)
The phrase "quick-start" can be misleading in hardware projects, but here's a list of things you'll need to set up this platform [(Full details in the Wiki)](https://github.com/Leenix/StreetFighter_Sensor_Testbed/wiki):
- Arduino Yun (with 4GB card) or Arduino Leonardo (for the non-logging, non-WiFi version)
- StreetFighter PCB
- Traffic sensors (sonar, lidar, PIR)
- Environmental sensors (temperature, humidity, illuminance, IR temperature, noise)
- Some kind of long-range network transceiver (XBee socket)

After you get all all that, you just need to populate the PCBs, wire up the sensors, configure the Yun software, build and upload the Arduino-side firmware, power the platform somehow, and then you're golden.

# [Features](https://github.com/Leenix/StreetFighter_Sensor_Testbed/wiki/Features)
## Traffic detection
- PIR sensor detects generic movements from vehicles, cyslists, and pedestrians
- Sonar/Lidar counts vehicles over a single lane

## Environmental monitoring
- Ambient temperature
- Relative humidity
- Illuminance
- Ambient noise
- Road temperature
- Road flood level

## Lamp health and control
- Luminaire temperature
- Power consumption
- Dimming interface

## Other
- Smartphone detection using Wifi and/or Bluetooth
- Public WiFi AP (if wired connection is provided)

# [Documentation](https://github.com/Leenix/StreetFighter_Sensor_Testbed/wiki)
- Full installation documentation can be found on the [Wiki](https://github.com/Leenix/StreetFighter_Sensor_Testbed/wiki)
- Code documentation is inside the code. No external reference just yet.

# [License](http://www.gnu.org/licenses/gpl-3.0.en.html)

This project is licensed under the terms of the GNU General Public License v3.0.
