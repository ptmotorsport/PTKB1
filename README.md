# PTKB1
CANbus Keyboard using an Arduino Nano and MCP2515

Thank you for your interest in this PT Motorsport Arduino project! We’re very excited to be able to share this project with you.

Projects like these are made possible by your support through purchases on the PT Motorsport AU website.

www.ptmotorsport.com.au

Thank you for your support! We greatly appreciate you spreading the word about our products and services to your fellow motorsport enthusiasts.

# Hardware
This code is writen to support the following hardware
 - Arduino Nano
 - MCP2515 with TJA1050 operating with an 8Mhz crystal
 - 8 momentairy buttons of your choosing wired into the Digital inputs
 - NeoPixel LED strip - 8 LEDs

# About
This code will roughly emulate a Blink Marine PKP2400si to an extent, not all features and operations are setup.
Features that are setup include
- Button presses transmitted
- Tick Timer with button presses
- LEDs light up according to received CAN messages
- Change CAN Speed according to received CAN messages (after reboot)
- Change backlight LED birghtness according to received CAN messages


# Licence
Copyright (c) 2023 - PT Motorsport AU Pty Ltd

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
