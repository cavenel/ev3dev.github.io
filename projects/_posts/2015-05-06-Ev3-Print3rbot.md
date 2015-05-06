---
author: "@cavenel"
programming_language: Python
youtube_video_id: 9pjpQoZoW6E
source_code_url: "https://github.com/cavenel/ev3-print3rbot/"
building_instructions_url: "https://www.dropbox.com/s/5jtnpaf18ibalj0/ev3_Print3rbot.pdf?dl=1"
excerpt: "An ev3 robot that draws with a pen"
---

The ev3 Print3rbot can be built using the EV3 Home Edition set, plus a [3D printed pen holder](http://www.thingiverse.com/thing:409421), 2 [LEGO Gear Wheel 40T](http://www.thingiverse.com/thing:409421) (ref. 4285634) and an additional push button sensor (EV3 or NXT). The additional push button and the 2 gears are included in the EV3 education set.

The robot can draw simple svg files (as long as it only contains non transformed paths). See images/template.svg.
The python code is using the [Python API](https://github.com/ddemidov/ev3dev-lang-python) from @ddemidov. To install it:

* Prerequisites:

```
apt-get install libboost-python-dev python-setuptools python-pil
```

* Now, the actual module installation:

```
easy_install http://ddemidov.github.io/ev3dev-lang-python/python_ev3dev-latest.egg
```

The ev3dev version must be at least [ev3dev-jessie-2015-05-01](https://github.com/ev3dev/ev3dev/releases/tag/ev3dev-jessie-2015-05-01).

## Example of extension for the Ev3 Print3rbot:

YT("UwpghsdmDsE", print = TRUE)

[![EV3 Print3rbot PlotClock ](http://img.youtube.com/vi/UwpghsdmDsE/0.jpg)](https://www.youtube.com/watch?v=UwpghsdmDsE)