# Alarmo-Keypad
WT32-SC01 Plus Alarmo keypad for use in Home Assistant with some special sauce

Since there was no nice readily available keypad for the Alarmo integration in Home Assistant we decided to create our own

- Uses WT32-SC01 Plus display with integrated ESP32S3
- Supports Arm-Away / Arm-Night / Arm-Home
- With chameleon function to scramble the keypad every time it is used
- Works great with the Konnected alarm panel modules to build your own Home Alarm
- Speakers used: 20mm version  https://a.aliexpress.com/_EGAeVFw

Install:
- create a new device in ESPHOME for your WT32-SC01 Plus
- copy the main yaml file in your newly created device but keep your unique api: encryption key
- copy the WAV files to the esphome folder
- hit install in ESPHOME
- If needed tweak the settings in the substitutions: section to suit your needs
