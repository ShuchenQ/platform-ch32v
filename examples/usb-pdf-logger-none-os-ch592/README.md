How to build PlatformIO based project
=====================================

Project converted from https://github.com/openwch/ch592/blob/main/Application/PDF_DataLogger/CH592_PDF_Logger_USB.

1. [Install PlatformIO Core](https://docs.platformio.org/page/core.html)
2. Download [development platform with examples](https://github.com/Community-PIO-CH32V/platform-ch32v/archive/develop.zip)
3. Extract ZIP archive
4. Run these commands:

```shell
# Change directory to example
$ cd platform-ch32v/examples/usb-pdf-logger-none-os-ch592

# Build project
$ pio run

# Upload firmware
$ pio run --target upload

# Upload firmware for the specific environment
$ pio run -e genericCH592F --target upload

# Clean build files
$ pio run --target clean
```
