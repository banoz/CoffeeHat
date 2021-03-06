# Generic espresso machine control board

Arduino Nano-based control board for an espresso maker.

**WIP**

SubBoard_V1 is an extension board to use on top of MainBoard_V1 for Gaggiuino.

Pin mapping:  

```
A0 - Pressure transducer

A1 - CLK  \
A2 - D1    -- dual HX711 scales
A3 - D2   /

A4 - I2C SDA
A5 - I2C SCL

D8 - Brew switch
D7 - Steam switch

D0 - NEXTION TX
D1 - NEXTION RX

D3 - AC zero-crossing

D4 - DO   \
D5 - CS    -- MAX31855
D6 - CLK  /

D9 - 3-way valve control
D10 - Pump TRIAC control
D11 - Boiler heater SSR control
```

![SubBoard_V1_sch](https://github.com/banoz/CoffeeHat/blob/main/Hardware/MainBoard_V1/EAGLE/Exports/SubBoard_V1_sch.png)
![SubBoard_V1_top](https://github.com/banoz/CoffeeHat/blob/main/Hardware/MainBoard_V1/EAGLE/Exports/SubBoard_V1_top.png)

![MainBoard_V1_sch](https://github.com/banoz/CoffeeHat/blob/main/Hardware/MainBoard_V1/EAGLE/Exports/MainBoard_V1_sch.png)
![MainBoard_V1_top](https://github.com/banoz/CoffeeHat/blob/main/Hardware/MainBoard_V1/EAGLE/Exports/MainBoard_V1_top.png)
