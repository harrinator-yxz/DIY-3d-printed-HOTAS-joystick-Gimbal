# DIY-3d-printed-HOTAS-joystick
## What is this repositiory for?
this repo is for notes and files to help built a diy fully 3d printed HOTAS joystick that uses STM32 and hid. it will include files along with some instructions links, pictures and software to help you along your journey.


## about

Harrinator-YXZ's 3D printed joystick gimbal is a 2/3 axis CAM based gimbal for HOTAS joysticks and sidesticks. It uses hall effect sensors (SS49E). I personaly used and STM32 to handle the USB HID input with [Freejoy](https://github.com/FreeJoy-Team/FreeJoy)


## Images and examples:
<img src="/Images/final.png" alt="render" width="1200" />

<img src="/Images/gimbal v27.png" alt="render" width="1200" />

<img src="/Images/cam1.png" alt="render" width="400" />
<img src="/Images/cam2.png" alt="render" width="400" />

## Software and usability.

This DIY Hotas joystick uses a STM32F103C8T6. This runs [Freejoy](https://github.com/FreeJoy-Team/FreeJoy) FreeJoy is a widely configurable game device controller based on the cheap STM32F103C8 microcontroller board. It allows you to create your own HOTAS, pedals, steering wheel device, etc, or customize a purchased one. 

I chose this because it is super configurable, has filtering, axis curves and supports heaps of censors.

## Hardware

I used SS49E's for my sensors for X and Y, a full BOM is yet to be made.

The whole joystick is 3d printed other than some bearings and magnets. 

The stick is hot swappble (WIP) but currently I have been testing using the [F-16 Sidestick Grip](https://www.printables.com/model/233472-f-16-sidestick-grip) By [Spock](https://www.printables.com/@Spock) On [printables.com](Printables). This is a really good but easy to print grip. For buttons I used 7mm momentary switches, and some PCB tactile switches and also tested some potentiometers.

When wiring it is important to share one ground acroos all components in the stick. I used two ethernet cables (CAT5 Network) and tightly wound these together making sure to remove the protective coating as there is very limited space.







