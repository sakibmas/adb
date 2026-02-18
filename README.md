# Pre-requisite
 - Download driver from https://adb.clockworkmod.com/
 - Install the driver.
 - Add the installation path to the PATH environment variable.
   
# Keycode Mapping Reference

This table maps numeric keycodes to their corresponding system events.

| KEYCODE | EVENT |
| :--- | :--- |
| 1 | SOFT_LEFT |
| 2 | SOFT_RIGHT |
| 3 | HOME |
| 4 | BACK |
| 5 | CALL |
| 6 | ENDCALL |
| 7 | 0 |
| 8 | 1 |
| 9 | 2 |
| 10 | 3 |
| 11 | 4 |
| 12 | 5 |
| 13 | 6 |
| 14 | 7 |
| 15 | 8 |
| 16 | 9 |
| 24 | VOLUME_UP |
| 25 | VOLUME_DOWN |
| 26 | POWER |
| 27 | CAMERA |
| 28 | CLEAR |
| 61 | TAB |
| 64 | BROWSER |
| 65 | MAIL |
| 66 | ENTER |
| 82 | MENU |
| 83 | NOTIFICATION |
| 84 | SEARCH |
| 279 | PASTE CODE |

# Basic commands
 - ```
   adb devices  
   ```
     &ensp;  List of devices attached  
     &ensp;  236f489a     &emsp;   device
 - ```
   adb shell  
   ```
      ```
        input keyevent 26
      ```
      ```
        input swipe 300 1000 300 500
      ```
      ```
        input text 1234 && input keyevent 66  
      ```
      ```
        pm list packages
      ```
      ```
        top -b -n 1 -d 0.1 -o %CPU,%MEM
      ```
      ```
        pm uninstall -k --user 0 com.mi.globalbrowser
      ```
      ```
        dumpsys battery
      ```
      ```
        reboot -p
      ```


