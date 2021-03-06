# Meaty-3+
Meaty-3+ is a micro USB connected Basic Breakout for the FTDI FT231XS USB to serial IC. It's a "springboard" from the Sparkfun "Beefy-3" USB-Serial board with some additional capabilities.

Version 3 includes an improved micro-USB plug and updated documents.

Boards are available from OSH Park:<a href="https://oshpark.com/shared_projects/OyBMIKnf"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>
![](https://github.com/mdlougheed/Meaty-3/blob/master/Photos/20181228_105148.jpg)

The Meaty-3+ brings more power output, using a Torex Semiconductor 1 Amp XC6220B331MR-G linear 3.3V regulator. That's a whopping 66% power output increase (up to your USB power supply current limit - of course)! It also features on-board selectable CTS input or RTS output using a solder jumper.

This board will auto-reset any Arduino board that has the (DTR) reset pin brought out to a 6-pin connector (Arduino, Lilypad, etc) - AND can be configured for auto-resetting boards that use the RTS signal, as well as auto-reset/auto-program ESP-8266 & EPS-32 based boards that use the NodeMCU style DTR/RTS transistor crossover reset circuit (NodeMCU, ESP8266, ESP-01, Huzzah). In other words, you have flexibility!

This pluggable serial adapter, simplifies your application board when the power and cost expense of USB serial connectivity isn't always needed.

