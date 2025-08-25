# babygrand
Baby Grand, a mechanical keyboard, designed by me.
This keyboard is a minimalistic 31-key, alpha-staggered, choc only caseless board. 

Layout:

![babygrandkle](https://user-images.githubusercontent.com/55664712/127396753-f90141ba-83c4-42b9-89fb-d9631638a62b.png)

some pics:

![photo_2021-07-22_08-27-34](https://user-images.githubusercontent.com/55664712/127390575-40a80c1e-cb9b-4062-9069-d2af6b2e2beb.jpg)
my pic

![photo_2021-07-22_08-27-47](https://user-images.githubusercontent.com/55664712/127390579-d408f549-03de-40ba-9969-9b1a87f240a7.jpg)

ottimo's babygrand (thank you ottimo!)

![photo_2021-07-28_13-22-46](https://user-images.githubusercontent.com/55664712/127390581-4185c5bf-42b4-4379-8ea1-0de87ba8f0fa.jpg)

my pic again, now with the PCBs

## Get your own
Build with standard SMD keyboard diodes, any CHOC-type low-profile switch, and any pro micro/equivalent. Using whatever custom QMK environment (I recommend QMK MSYS) you use for other keyboards, add `babygrandv2` to your `keyboards` folder, edit the keymap, compile and flash. 

## About the project
I created the circuit board using KiCAD, and wrote the firmware by adapting that of other ATMEGA32-based keyboards. This repository contains Gerber files, and QMK configurations. Note: This is not a 'custom keyboard'  This keyboard existed as a group order, and I sold the last one several years ago. If you would like your own, you will have to order your own circuit boards, diodes, switches, and a Pro Micro-standard controller. You will have to manually flash it using QMK. As this was a learning experience, please do not expect any sort of support for this keyboard in the future. Created during my tenure in the 40% keyboard community.

## Resources
Firmware: 
https://qmk.fm/

Ordering PCBs:
https://www.reddit.com/r/MechanicalKeyboards/comments/mujaom/what_are_my_options_for_ordering_a_pcb_from_a/

Example of what building your own keyboard from scratch entails:
https://medium.com/@ParityB1t/gherkin-build-log-da6cbfce1ae0
