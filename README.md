# Battery Alert Microsoft VBScript
Script from this website: https://www.thewindowsclub.com/create-laptop-battery-full-charge-notification

The .vbs file would be placed at the following file directory to have the script at startup:
```
C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp
```

Edited for an Asus Laptop with the battery limit set to 80%.

As USB-C charging does not have power passthrough, the battery is charged to the set limit and the battery is discharged until below 79%.

This script would remind myself to unplug the laptop to prevent excess battery cycles.
