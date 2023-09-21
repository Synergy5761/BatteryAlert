# Battery Alert Microsoft VBScript
Orginal script from this website: https://www.thewindowsclub.com/create-laptop-battery-full-charge-notification

Edited for an Asus Laptop with the battery limit set to 80%. Specific alert at 79%.

The .vbs file would be placed in the following location for the script to start with each boot:
```
C:\ProgramData\Microsoft\Windows\Start Menu\Programs\StartUp
```

As USB-C charging does not have power passthrough, the battery is charged to the set limit and the battery is discharged until below 79%.

This script would remind myself to unplug the laptop to prevent excess battery cycles.
