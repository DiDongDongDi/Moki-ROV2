# Moki-ROV2 Arduino software
## The "develop" branch may not even compile! or run!!

There are 2 directories here;

# Develop
```
As said before, this may not even run or do anything!
It should not crash your ROV or do anything worse.
```

# Stable
```
Just use this version and you will be a happy camper!
```

# PlatformIO cli commands (debug only)
```
platformio init -b uno (for Arduino Uno)
platformio init -b megaatmega2560 (for Arduino Mega2560)
platformio init -b teensy31 (for Teensy 3.2)
platformio run
platformio run --target upload
platformio device monitor -p /dev/ttyACM0
```

## License

The MIT License

Copyright (c) 2017 by Eric van Dijken <rov-pi@team-moki.nl>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.