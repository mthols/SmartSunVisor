# SmartSunVisor
Repository for our senior project 21-22

Click on "Main_Program" for the main code to go on the ESP32-WROOM-32E.

Click on "Smartphone_App" for the code to create the Android application.

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

#### Limit Switches

IO13 -> Door window

IO19 -> Windshield
