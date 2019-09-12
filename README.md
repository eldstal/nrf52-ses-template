# nrf52-ses-template
A Segger Embedded Studio project template for building outside the Nordic SDK directory
The project contains build rules to switch between the NRF52840-DK development kit (DK) and
the  NRF52840 Dongle (Dongle).

The code is based on the led_softblink example from the SDK.

1. Set up the global macro `$(SDKDir)` in segger to point to the root of your Nordic SDK.
2. Put your project wherever you want and open the solution in Segger.

![The segger options dialog](https://i.imgur.com/M7c6d4s.png "Setting global macro")
