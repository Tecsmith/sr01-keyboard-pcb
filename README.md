# VR01-Keyboard-PCB

<p align="center"><img src="docs/donotbuild.min.svg" alt="Under Construction" width="320"></p>

## Intent

A 1-key<small><sup>1</sup></small> *"keyboard"* with QMK f/w.

> <sup>1</sup> = maybe 1 key, since that is optional.  Also optional is the WiFi receiver :smile:


## Planned Features

- [ ] QMK build
- [ ] MCU *TBD.* *(must be something small; ¿LQFP-32 footprint => `STM32F042K6T6`?)*
- A few options *(i.e. 1 PCB with option cut-aways + <abbr title="Do Not Populate">DNP</abbr> build sets)*:
  - [ ] Option: 1-key support, MX or Choc *(:bulb: from [Adafruit NeoKey Trinkey](https://www.adafruit.com/product/5020))*
  - [ ] Option: Rotary Encoder *(:bulb: from [Adafruit Rotary Trinkey](https://www.adafruit.com/product/4964))*
  - [ ] Option: ESP32 receiver *(:bulb: from [https://store.aprbrother.com/product/wifi-hid-injector](WiFi HID Injector))*
  - [ ] ?? IR receiver *(:bulb: from [Snipeye Uno V4](https://switchoddities.com/products/uno-v4-usb-c))*
  - [ ] ?? `TTP223` Touch module


## Why?

When I built the VR61, one of the MicroMod modules I wanted to build for was the [SparkFun MicroMod ESP32 Processor](https://www.sparkfun.com/products/16781).. and for that I bought a [April Brother WHID Cactus](https://store.aprbrother.com/product/wifi-hid-injector) ... and then never got around to it.

The intent was to create a Wireless KB *(like a BT or 2.4GHz KB, but with WiFi)*, and also a whole bunch of additional features like a virtual web-KB, or the ability to configure the keys via it's own web interface.

This project is that idea, but modern.  *(The WHID Cactus is a ATmega 32u4 and ESP-12S combo.  Old and limited.)*

And then the tough was:  Why not also make it a Adafruit NeoKey Trinkey- / DigiSpark ATtiny85 USB key- ... -like 1 key?

## Possible BIG issues

- Finding a case for this.  BYO (3D printing) or source one ???.
- Ethical concerns with a WiFi KB, i.e. can be used as a hacker tool / "rubber ducky".
- Will need to got to `0402` footprints on the electronics, so harder to self build.

&nbsp;<br>&nbsp;

---
Made with :heart: by Vino Rodrigues
