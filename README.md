# SmartSunVisor
Repository for our senior project 21-22

## Some helpful links:
SPA Calculator: https://midcdmz.nrel.gov/solpos/spa.html

Calculating Solar Elevation (AKA Altitude) Angle: https://solarsena.com/solar-elevation-angle-altitude/

Calculating Solar Hour Angle: https://solarsena.com/solar-hour-angle-calculator-formula/

Calculating the maximum altitude for the sun on any given day:https://sciencing.com/calculate-suns-altitude-8556649.html

Calculating Solar Declination Angle: https://solarsena.com/solar-declination-angle-calculator/

ESP32-WROOM-32E Pinout
-----------------------------------------
#### Photovoltaic Cells

ADC1_CH6 -> IO34 -> Cell 1

ADC1_CH7 -> IO35 -> Cell 2

ADC1_CH4 -> IO32 -> Cell 3

ADC1_CH5 -> IO33 -> Cell 4

ADC2_CH8 -> IO25 -> Cell 5

ADC2_CH9 -> IO26 -> Cell 6

ADC2_CH6 -> IO14 -> Cell 7

ADC2_CH7 -> IO27 -> Cell 8

#### Track Motor 1 (uses DRV8825 driver) (Right)

IO16 -> Direction

IO17 -> Step

IO4 -> Enable

#### Track Motor 2 (uses DRV8825 driver) (Left)

IO5 -> Direction

IO18 -> Step

IO21 -> Enable

#### Visor Motor (uses DRV8825 driver)

IO22 -> Direction

IO23 -> Step

IO12 -> Enable

#### Limit Switches

IO13 -> Door window

IO19 -> Windshield
