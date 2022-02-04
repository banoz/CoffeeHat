# Generic espresso machine control board

WIP

SubBoard_V1 is an extension board to use MainBoard_V1 with Gaggiuino.

Pin mapping:

A0 - Pressure transducer

A1 - CLK  \
A2 - D1    -- dual HX711 scales
A3 - D2   /

A4 - I2C SDA
A5 - I2C SCL

A6 - Brew switch
A7 - Steam switch

D0 - NEXTION TX
D1 - NEXTION RX

D3 - AC zero-crossing

D4 - DO   \
D5 - CS    -- MAX31855
D6 - CLK  /

D8 - Boiler heater SSR control
D9 - 3-way valve control
D10 - Pump TRIAC control