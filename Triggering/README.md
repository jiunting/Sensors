## Example of Sensor Triggering with Arduino

* In this example, I use a photoresistor to trigger recording of thermocouple values

* The example uses the SPI communication. Details in: https://en.wikipedia.org/wiki/Serial_Peripheral_Interface

![][Exp_fig1] 

* From this setup, the thermocouple wire module MAX6675 only records temperature (red dots) when the voltage counts (i.e. controlled by photoresistor)(black line) below the threshold of 600.

* The example provide potential application to measure temperature during the day/night time and in sunny/cloudy day.


[Exp_fig1]:./figs/triggering.png "Photoresistor triggering mechansm"
