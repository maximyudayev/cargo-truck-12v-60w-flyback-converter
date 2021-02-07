# Heavy-Duty Truck 12V 60W Flyback DC/DC Converter
18V-32V input 12V output, 60W (5A) nominal 84W (7A) maximum, 60mm-by-30mm-by-25mm, no-opto flyback DC/DC converter with synchronous secondary rectifier, up to 97% efficiency, excellent static and dynamic output regulation for heavy-duty truck applications like interior appliances, ADAS, lighting, supplies for consumer electronics, etc.
![Graph: Efficiency and Duty Cycle vs Load](https://github.com/maximyudayev/cargo-truck-12v-60w-flyback-converter/blob/main/images/9.JPG)

Below is the efficiency and duty cycle graph as a function of load:
![Graph: Efficiency and Duty Cycle vs Load](https://github.com/maximyudayev/cargo-truck-12v-60w-flyback-converter/blob/main/images/7.png)

This DC/DC converter was built as part of my Power Electronics course at KU Leuven - Campus GroupT in academic year 2020-2021, taught by the awesome duo of Gert and Gorik :wink:

The converter was designed, built and tested. Results of the test can be found in the final report of the course, which also includes all the detailed calculation steps and side-by-side comparison to a synchronous buck converter designed and built by my lab partner Matthias.

## Features
- [X] Clean, readable and well-documented
- [X] Operating range of normal battery voltages
- [X] <500mV input/output ripple
- [X] Low-cost prototype
- [X] Dual-variant primary clamp
- [X] Dual-variant secondary rectifier
- [ ] TVS circuit on the input
- [ ] Multiple output rails (5V, 3V3)
- [ ] Dynamic load ripple under 50-100mV
- [ ] Heat management #1

PCB front side:
![PCB front side](https://github.com/maximyudayev/cargo-truck-12v-60w-flyback-converter/blob/main/images/60W%2024V%20to%2012V%20Flyback%20Front.png)

PCB back side:
![PCB back side](https://github.com/maximyudayev/cargo-truck-12v-60w-flyback-converter/blob/main/images/60W%2024V%20to%2012V%20Flyback%20Back.png)

All the design files are under GPL3 and can be freely used for personal projects where this device can be of use.