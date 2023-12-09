# Homey Heating Manager

Adds functionnalities to manage your house heaters.

Provide:
- App configuration screens to:
    - Define user named temperature (unfreeze, cold, warm, ...), including default settings
    - Define area (kitchen, 1st Floor, ...)
    - Defined several temperature setting per area (summer, winter, ...)
    - Copy temperature settings from an area to another
    - Set default redo delay
    - Set default temperature unchanged security delay
- Area device:
    - Allow to override temporarily the target temperature
    - Allow to change active state (on/off)
    - Includes flow cards to switch active state and setting (summer, winter, ...)
    - Configuration screen to modify this area settings (shortcut to app settings but limited to this area)
- Thermostat device:
    - Allow to assign an area
    - Retrieve target temperature from assigned area active setting
    - Retrieve current temperature from the room sensors
    - Includes flow cards to switch area and thermostat state (on/off)
    - Turn on / off heaters
    - Configuration screen to:
        - Set thermostat perimeter (room or area)
        - Exclude sensors (temperature / door / window) or heaters
        - Include sensors from another room or area (temperature / door / window)
        - Set redo delay
        - Set temperature unchanged security delay
