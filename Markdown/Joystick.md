# Steam Controller (2015) Joystick Information

## Joystick Cap
- [Joystick Cap Swap / Upgrade For The Steam Controller](https://www.youtube.com/shorts/JH8CmCkltzY)
- [My little journey in swapping my Steam Controller's joystick cap](https://www.reddit.com/r/SteamController/comments/xm92cj/my_little_journey_in_swapping_my_steam/)
- ["The Original Steam Controller." - Joystick Cap Replacements (Timestamped)](https://youtu.be/DlmwQlGzo7E?si=ruu_2Ahioq27Ts4h&t=1493)
    - Technical TL;DW:
        - Valve's Steam Deck joysticks work, [they can be purchased without the whole joystick modules from ExtremeRate](https://www.extremerate.com/products/extremerate-replacement-thumbsticks-with-original-touch-sensing-for-steam-deck-lcd-oled-black-gray)
            - Make sure to keep the wire from getting into the way when using the joystick, either glue it down or cut it out
            - You can also get the caps from joystick modules by desoldering or cutting the capacitive touch wire
        - [8BitDo SN30 Pro, SN30 Pro+, Pro2 Joystick Rubber Replacements](https://shop.8bitdo.com/products/8bitdo-sn30-pro-sn30-pro-pro2-joystick-rubber-replacement-1-pcs) should work as well

## Joystick Module

### Joystick Calibration
- ["The Original Steam Controller." - Testing The Stock And Custom Joysticks (Timestamped)](https://youtu.be/DlmwQlGzo7E?si=EgGjieBNeZh2RAyJ&t=1541)
    - Technical TL;DW:
        - Steam's built in calibration tool doesn't seem to do anything apart from making the controller beep
        - The joysticks calibrate themselves each session after they are used
        - You can test controllers' circularity using the [Hardware Tester - Gamepad Tester website](https://hardwaretester.com/gamepad)

### Stock Module
- Manufacturer: ALPS
- Pinout: Doesn't match PS4, PS5 or Xbox Series

### Custom Hall-Effect / TMR Module
- [Replaced the joystick with Hall Effect sensors on Steam Controller](https://www.reddit.com/r/SteamControllerMods/comments/1drrrtd/replaced_the_joystick_with_hall_effect_sensors_on/)
- [Steam Controller: I can has Hall Effect module!](https://lemmy.ml/post/16810625)
- ["The Original Steam Controller." - TMR Joystick Module Upgrade (Timestamped)](https://youtu.be/DlmwQlGzo7E?si=b_opruGgVmdWSLr6&t=811)
    - Technical TL;DW:
        - [Soldering Guide](./Soldering.md)
        - Get pinout of original joystick module using a voltmeter in continuity mode
        - Desolder the old module
        - Make a new joystick module that matches the original one
            - Eg.: get 2 Xbox modules and swap the side parts
        - Solder in the new module