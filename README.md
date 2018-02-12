[![ TSL45315](TSL45315_I2C.png)](https://store.ncd.io/product/tsl45315-ambient-light-sensor-3-lux-to-220k-lux-i2c-mini-module/).

#  TSL45315

Manufactured by AMS-TAOS USA Inc., the TSL45315 device provides ambient light sensing (ALS), giving direct lux output that approximates human eye response under a variety of lighting conditions.
This Device is available from www.ncd.io 

[SKU: TSL45315]

(https://store.ncd.io/product/tsl45315-ambient-light-sensor-3-lux-to-220k-lux-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface TSL45315 ambient light sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/tsl45315-ambient-light-sensor-3-lux-to-220k-lux-i2c-mini-module/">TSL45315 ambient light sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python TSL45315.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
