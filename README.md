**<DISCLAIMER>** This library has been duplicated from the original source at https://github.com/sparkfun/SparkFun_BME280_Arduino_Library. Additional files applicable to the workshops have been added under the "/examples" folder to allow for straightforward installation with the Arduino IDE.

SparkFun BME280 Arduino Library
========================================

![SparkFun BME280 Breakout](https://cdn.sparkfun.com//assets/parts/1/2/3/2/9/14348-01.jpg)

[*SparkFun CCS811/BME280 Combo (SEN-14348)*](https://www.sparkfun.com/products/14348)

This library allows the user to:

* Read pressure in Pa
* Read temperature in C
* Read humidity in %RH

It also provides the following mathematical functions based from the above.

* Read temperature in F
* Read altitude in meters
* Read altitude in feet

Some examples include a circular buffer class for averaging.

Repository Contents
-------------------

* **/examples** - Example sketches for the library (.ino). Run these from the Arduino IDE. 
* **/extras** - Additional documentation for the user. These files are ignored by the IDE. 
* **/src** - Source files for the library (.cpp, .h).
* **keywords.txt** - Keywords from this library that will be highlighted in the Arduino IDE. 
* **library.properties** - General library properties for the Arduino package manager. 

Documentation
--------------

* **[Installing an Arduino Library Guide](https://learn.sparkfun.com/tutorials/installing-an-arduino-library)** - Basic information on how to install an Arduino library.
* **[Product Repository](https://github.com/sparkfun/BME280-Breakout-Board)** - Main repository (including hardware files) for the SparkFun BME280 Breakout.
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/sparkfun-bme280-breakout-hookup-guide)** - Basic hookup guide for the SparkFun BME280 Breakout.

Products that use this Library 
---------------------------------

* [*SEN-14348*](https://www.sparkfun.com/products/14348)
* [*SEN-13676*](https://www.sparkfun.com/products/13676)

Version History
---------------

* [V_1.0.0](https://github.com/sparkfun/SparkFun_BME280_Arduino_Library/tree/V_1.0.0) - Public release.
* [V_1.1.0](https://github.com/sparkfun/SparkFun_BME280_Arduino_Library/tree/V_1.1.0) - Pulled request to add decimal precision to readFloatPressure() and readFloatHumidity().
* [V_1.2.0](https://github.com/sparkfun/SparkFun_BME280_Arduino_Library/tree/V_1.2.0) - Added ESP32 architecture directives to modify begin operation.
* [V_2.0.0](https://github.com/sparkfun/SparkFun_BME280_Arduino_Library/tree/V_2.0.0) - Major update. Generalized wire port. Functionalized oversampling, standby time, etc. Added setMode.


License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact techsupport@sparkfun.com.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
