# Steam-Controller
Information about the Steam Controller's firmware and hardware modifications / repairs.

## Firmware Information
- Initially the controller only worked with a wired connection or wirelessly with a USB receiver
- [An update was released later](https://help.steampowered.com/en/faqs/view/1796-5FC3-88B3-C85F) so the controller can now be used with Bluetooth Low Energy (BLE) as well
    - Some guides I found on how to update the firmware in case the method in the link above doesn't work:
        - [Update Steam Controller firmware after the removal of legacy Big Picture mode](https://www.reddit.com/r/SteamController/comments/17ocq8b/guide_update_steam_controller_firmware_after_the/)
        - [How to update/configure/link your steam controller](https://steamcommunity.com/sharedfiles/filedetails/?id=3150369779)

### Using Bluetooth / USB Receiver Modes
- BLE Pairing - Steam + Y
- Receiver Pairing - Steam + X
- Switch To BLE Mode - Steam + B
- Switch To Receiver Mode - Steam + X

### Settings
- Steam button LED brightness
- Power on / off sound
- Trackpad & joystick calibration

### Revert firmware of SteamVR dongle to work with Steam Controller [guide by u/Hilltopy](https://www.reddit.com/r/SteamController/comments/11wjudj/comment/jczv38d/)
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

TODO: Add confirmation about it still working & Linux guide

## Disassembling The Controller

### Tools Needed

## Hardware Modifications / Repairs

### CAD Files / 3D Models
- [Official CAD Release](https://store.steampowered.com/news/app/353370/view/3931035846865618326)
- [Additional 3rd Party Models - Includes Missing Ones From The Official Release](https://github.com/MichaelZaugg/OpenSteamController-Continued/tree/master/Mods/CAD-Releases)

### Joystick
- [Hall Effect / TMR Module Replacement](https://www.reddit.com/r/SteamControllerMods/comments/1drrrtd/replaced_the_joystick_with_hall_effect_sensors_on/)
- [Cap Upgrade / Replacement](https://www.youtube.com/shorts/JH8CmCkltzY)

### Trackpads
- [Quieter And Easier To Press](https://www.youtube.com/shorts/NYpm2bWQAME)

### Bumper Buttons
- [Quieter And Easier To Press](https://www.youtube.com/shorts/ARzfF4CxAJA)

### Triggers

### Front Plate Buttons
- [Update on Steam Deck face button mod](https://www.reddit.com/r/SteamControllerMods/comments/1erquuf/update_on_steam_deck_face_button_mod/)

### USB Port
- [Usb-C steam controller](https://web.archive.org/web/20201119024700/https://www.reddit.com/r/SteamController/comments/i0pzzy/)
    - [Wiring Guide](https://web.archive.org/web/20220713150853/https://i.imgur.com/dqzbJLd.jpg)
- [USB-C Steam Controller mod + aluminum thumbstick](https://www.reddit.com/r/SteamControllerMods/comments/1bs75w9/usbc_steam_controller_mod_aluminum_thumbstick/)

## Additional Resources & Interesting Things
- [iFixit Guides And Teardowns](https://www.ifixit.com/Device/Steam_Controller)
- [OpenSteamController-Continued](https://github.com/MichaelZaugg/OpenSteamController-Continued)
- [r/SteamController](https://www.reddit.com/r/SteamController/)
- [r/SteamControllerMods](https://www.reddit.com/r/SteamControllerMods/)
- [Steam Controller Discord](https://discord.com/invite/BuANgkG)
- [3D Printable Models For The Steam Controller](https://www.yeggi.com/q/steam+controller/)
- [Steam Controller - General Discussions](https://steamcommunity.com/app/353370/discussions/)
- [Steam Controller - News Hub](https://store.steampowered.com/news/app/353370/)
- [Steam Controller - Store Page](https://store.steampowered.com/app/353370/Steam_Controller/)
- [Steam Controller - Wikipedia Page](https://en.wikipedia.org/wiki/Steam_Controller)
- [Steam Controller & Steam Link Box Scans](https://archive.org/details/steam-link-steam-controller-box-scans/)
    - [Box Art Inspired Renders](https://www.reddit.com/r/SteamControllerMods/comments/1lmvo7q/steam_controller_renderings_box_art_inspired_8k/)
- [Transparent Valve Hardware Team Exclusive Steam Controller](https://www.reddit.com/r/SteamController/comments/6lrg7g/just_realized_ive_never_shared_this_here/)
    - [Image of the backside by u/Plagman](http://imgur.com/a/7PORl)