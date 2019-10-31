---
layout: post
title: MacOS Battery Icon Disappear Issue
date: 2019-10-30 22:32 -0400
---
## Symptoms
1. The Battery Icon on MacOS(for me it happened on MacOS Catalina), dissappears without any reason.
![Battery Icon](/assets/images/Screen Shot 2019-10-30 at 22.15.04.png)
1. The fan of the laptop is running without any considerable process hogging the CPU cycles.
1. Even after you check the tick mark on System Preferences, it unchecks itself immediately and then battery icon dissappears after showing itself for a brief moment.
![Battery Option](/assets/images/Screen Shot 2019-10-30 at 22.17.00.png)

## One of the thing which worked for me:
- Apple official page defines SMC as System Management Controller which is mostly responsible for battery management, thermal management, keyboard backlight, etc
- This is what I tried as first defence against the symptoms presented above:
-  Resetting the SMC which is pressing the `CTRL + SHIFT + OPTION + COMMAND + POWER Button` restarts the laptop.

<br/>
![Keyboard Image](/assets/images/Screen Shot 2019-10-30 at 22.04.50.png)

## Results:
- After this Power Mag charger started lighting up indicating that it was charging the battery.
- Second the battery icon started appearing.
- CPU fan started calming down.

References:
- [Apple Support](https://support.apple.com/en-us/HT201295)
