# Steam Controller Firmware Information
- Initially the controller only worked with a wired Micro-USB connection or wirelessly with a USB receiver
- [An update was released later](https://help.steampowered.com/en/faqs/view/1796-5FC3-88B3-C85F) so the controller can now be used with Bluetooth Low Energy (BLE) as well
    - Some guides I found on how to update the firmware in case the method in the link above doesn't work:
        - [Update Steam Controller firmware after the removal of legacy Big Picture mode](https://www.reddit.com/r/SteamController/comments/17ocq8b/guide_update_steam_controller_firmware_after_the/)
        - [How to update/configure/link your steam controller](https://steamcommunity.com/sharedfiles/filedetails/?id=3150369779)

## Using Bluetooth / USB Receiver Modes
- BLE Pairing - Steam + Y
- Receiver Pairing - Steam + X
- Switch To BLE Mode - Steam + B
- Switch To Receiver Mode - Steam + X

## Settings
- Steam button LED brightness
- Power on / off sound
- Trackpad & joystick calibration

## Revert firmware of SteamVR dongle to work with Steam Controller [guide by u/Hilltopy](https://www.reddit.com/r/SteamController/comments/11wjudj/comment/jczv38d/)
> I dunno if it'll work for the Tundra Super dongle, but I know you can revert the firmware on the base steamVR dongle they sell to SC just fine, as it's the exact same model as what the SC came with. I assume it would also likely work for purpose-built single controller VR dongles, but haven't checked.
>
> Anyway, here's how you can change the firmware for a 1002 dongle back to Steam Controller mode:
>
> - Make sure you have SteamVR downloaded
> - Open 2 copies of windows explorer
> - Send 1 to whatever\Steam\controller_base and copy d0ggle.bin
> - Open the other to whatever\Steam\steamapps\common\SteamVR\tools\lighthouse\firmware and paste d0ggle.bin there (may need to be under firmware\vr_controller\archive depending on how Steam reacts)
> - Close Steam completely and make sure any and all VR stuff is unplugged
> - Go back to tools\lighthouse and shift + right click, then open a Powershell window there
> - Copy paste "bin\win32\lighthouse_watchman_update.exe -e firmware\vr_controller\archive\d0ggle.bin" there and hit enter
> - a. You should see Windows say a Boot ldr is being loaded
> - Open Steam back up, Windows should say it’s configuring a Steam Controller now
> - Go to settings, controller, general controller settings, then add new controller
> - Enjoy!

TODO: Add confirmation about this still working & Linux guide