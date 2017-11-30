nrf52-ble-app-uart-long-range
=============================

This repository contains modified version of the ble_app_uart and ble_app_uart_c applications, which support the long range mode provided by S140 v6.0.0-6 alpha

The ble_app_uart example will advertise on long range, and the ble_app_uart_c application will scan and connect over long range. 

Requirements
------------
- [nRF5 SDK version 14.2.0](http://developer.nordicsemi.com/nRF5_SDK/nRF5_SDK_v14.x.x/nRF5_SDK_14.2.0_17b948a.zip) 
- [nRF52840-PDK](https://www.nordicsemi.com/eng/Products/nRF52840-Preview-DK) development kit 
- Keil uVision or Segger Embedded Studio

To compile it, clone the repository into the *\nRF5_SDK_14.2.0\examples\ble_central_and_peripheral\* folder.

About this project
------------------
This application is one of several applications that has been built by the support team at Nordic Semiconductor, as a demo of some particular feature or use case. It has not necessarily been thoroughly tested, so there might be unknown issues. It is hence provided as-is, without any warranty. 

However, in the hope that it still may be useful also for others than the ones we initially wrote it for, we've chosen to distribute it here on GitHub. 

The application is built to be used with the official nRF5 SDK, that can be downloaded from [http://developer.nordicsemi.com/nRF5_SDK/](http://developer.nordicsemi.com/nRF5_SDK/)

Please post any questions about this project on [https://devzone.nordicsemi.com](https://www.nordicsemi.com/)
