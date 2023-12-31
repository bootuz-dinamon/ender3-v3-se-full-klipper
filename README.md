# ender3-v3-se-full-klipper

Klipper config for Creality Ender-3 V3 SE with driver section.

For CR4NS200320C13_32_MS35774_GD303RET6 mainboard (M4 label).
https://s.click.aliexpress.com/e/_Dmdyedv


With current control for stepper motors.
Now the motors do not overheat.

This is a complete configuration, it is enough for Klipper to work fully.

There is also a compiled file klipperXX_xxxxxxxxx.bin  v0.12.0-303, but I recommend compiling this file yourself.

klipper12_type_c.bin   - for connection via type-c connector (USART1 PA10/PA9).

klipper12_LCD_connector.bin  - for connection via IDC 10 pin LCD connector (USART3 PB11/PB10).


After installation you need to do:
1. Bed mesh calibrate
2. Manual calibrate Z-offset
3. Calibrate bed and extruder PID.

https://youtu.be/LrBiwabN-Y8

[![IMAGE ALT TEXT](http://img.youtube.com/vi/LrBiwabN-Y8/0.jpg)](http://www.youtube.com/watch?v=LrBiwabN-Y8 "Creality Ender3 V3 SE Klipper")
