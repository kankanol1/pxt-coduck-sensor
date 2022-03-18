# PTX (Makecode) Blocks for the MonkMakes Sensor for micro:bit.




## Installation

From your Blocks code editor, click _Advanced_ and then _Extensions_. Next, enter the url: 

https://github.com/kankanol1/pxt-coduck-sensor.git

into the search field at the top of the screen.

Once the extension is added, you will find a new blocks category called _Sensor_


## Examples

First wire up your Sensor to your micro:bit like this.

![Sensor blocks category](https://github.com/kankanol1/pxt-coduck-sensor/blob/master/figs/connecting.png?raw=true)


### Detecting Claps

The _sound level_ block returns a value between 0 and 100 depending on the overall level of sound that the microphone on the sensor is hearing.

This example reads the sound level and if it is above 20, it displays the YES image on the micro:bit's display for half a second. Try standing a few feet away from the sensor and clapping.

![Clap Detector](https://github.com/monkmakes/pxt-sensor/blob/master/figs/clap_code.png?raw=true)

Here's a link to the Makecode project: https://makecode.microbit.org/_WpsR1T5XpfE2


### Thermometer

The _temp c_ block returns the temperature measured by the board's thermistor in degrees Celcius. There is also a Fahrenheit version of the block.

This example will display the temperature every half second. Try putting your finger on the temperature sensor part of the Sensor board to warm it up.

![Thermometer](https://github.com/monkmakes/pxt-sensor/blob/master/figs/thermometer_code.png?raw=true)

Here's a link to the Makecode project: https://makecode.microbit.org/_c5qhvjTaR1u1


### Light Meter

The _light level_ block also returns a reading between 0 and 100. This example is very like the thermometer example, displaying the light level every half a second.

![Light Meter](https://github.com/monkmakes/pxt-sensor/blob/master/figs/light_meter_code.png?raw=true)

Shade the light sensor with your hand and the readings should decrease.

Here's a link to the Makecode project: https://makecode.microbit.org/_YUfPH3E7qbVc



## License
MIT


## Supported targets

* for PXT/microbit

