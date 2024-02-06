# Canvas Gateway Firmware

![Canvas Logo](img/canvas_logo.png)

Develop your custom BLE to cloud gateway with ease on one of the supported hardware platforms:

- [MG100](https://www.lairdconnect.com/iot-devices/bluetooth-iot-devices/sentrius-mg100-gateway-lte-mnb-iot-and-bluetooth-5)
- [Pinnacle 100 DVK](https://www.lairdconnect.com/wireless-modules/cellular-solutions/pinnacle-100-cellular-lte-m-nb-iot-bluetooth-5-modem)
- [BL5340 DVK](https://www.lairdconnect.com/wireless-modules/bluetooth-modules/bluetooth-5-modules/bl5340-series-multi-core-bluetooth-52-802154-nfc-modules)

Write your custom app in Python without worrying about compiling any code. Python support is based on the [MicroPython](https://github.com/micropython/micropython) engine.

**[Download release binaries here](https://github.com/LairdCP/Canvas_Gateway_Firmware/releases)**

This firmware is distributed as a `.hex` file for use with programming tools such as `nrfjprog` to program the internal flash of the supported boards via SWD interface. The `.bin` files included in the release package can be used to perform OTA firmware update via supported mobile application tools or from the cloud using LwM2M.

This firmware is a part of the <strong>Canvas Software Suite</strong> platform providing firmware, tools, documentation and sample applications to simplify software development on Laird Connectivity wireless products.
For more information about Canvas Software Suite see [https://www.lairdconnect.com/canvas]().
