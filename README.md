# portable_dc_alim_powered_by_usbB

## Description
This project purpose is to create a portable alim powerd by USB-B and cotrolable by a computer.

Here are the steps to follow :

    [X] Make the first Specifications
    [X] Check for USB-A Specifications
    [ ] choose a type of DC/DC converteur
    [ ] Make a first proof of concept
    [ ] Adjust specifications
    [ ] Make a first prototype


## Frist Specifications
### Power specifications

|Specifications|Min|Max|Unit|
|---|---|---|---|
|Output Voltage|0|20|V|
|Output Current|0|1|A|
|Output Power|0|20|W|
|Output Noise|0|1|%|
|Output Ripple|0|1|%|


- The alim should be powered by USB-A
- The output's noise must be 1% max
- The output's ripple must be 1% max
- The output's voltage must be adjustable by 0.1V
- The output's current must be adjustable by 0.1A

### Control specifications
- All the control must be done through the USB-A port
- The alim must be able to be controlled by a computer or dirrectly on the device

### Problème with the USB-A
Maximum output power of USB-A is 2.5W for USB 2.0 and 4.5W for USB 3.0. So the alim must be able to deliver 4.5W max.
In a 20V configuration, it leads to 225mA max. In a 5V configuration, it leads to 900mA max, in a 100% efficiency configuration.
This is not enough for a lot of applications. The alimentation therefore must have another power source.

### Possible solutions :
- Use a USB-B power source -> not suitable for a computer only device
- Use a battery
- Use a AC/DC converter from a wall plug
-


