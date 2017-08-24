# PowerMeter
Monitors power import/export and associated tarriffs

Basic:

An 'SDM220-Modbus' power meter is fitted into the main feed from the grid and measures both import and export power which can be read via a Modbus RTU interface over RS485 by an Arduino MEGA 2560.
A DS3231 RTC connected via IIC (I2C) provides the time of day so that the Day/night tarriffs can be calculated.
When exporting a GREEN light is lit to show it's okay to use power. When importing at peak rate a RED light is light to advise you to be economical with power. When importing at cheap rate a YELLOW light is lit to say it's not too dear now if you really need to use power.

Enhancements:

A micro SD card can be added to keep a log of power use.
A WiFi module may be added to allow reading of the log etc remotely.
