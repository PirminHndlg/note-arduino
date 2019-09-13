# [Blues Wireless][blues]

The note-arduino Arduino library for communicating with Blues Wireless Notecard via serial or I²C. Includes example sketches in the [examples directory](examples).

This library allows you to control a Notecard by writing an Arduino sketch in C or C++.
Your sketch may programmatically configure Notecard and send Notes to [Notehub.io][notehub].

This library is a wrapper around the [note-c library][note-c], which it includes as a git submodule.

This library is used by the [m5stack repo][m5stack] m5note Arduino sketch, which requires it to be installed per the instructions below.

## Installation

1. Download the library as a zip from 
   [here](https://github.com/blues/note-arduino/archive/master.zip)
or use the UI `Clone or Download` -> `Download ZIP`
2. Start the Arduino IDE
3. Import the library:
   ```
   Sketch -> Include library -> Add ZIP Library
   ```
And select the previously downloaded zip file.

[blues]: https://blues.com
[notehub]: https://notehub.io
[note-c]: https://github.com/blues/note-c
[m5stack]: https://github.com/blues/m5stack

