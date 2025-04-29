# digitdisplay.h

## Arduino-Library for 7-Digit-Displays.
This Library was designed for Hawlett-Paclard(HP) 5082-7653 displays, but can also be used with other displays if wired correctly.

## Usage:

    DigitDisplay digitDisplay(pin1, pin2, pin3, pin4, pin5, pin6, pin7)

    digitdipslay.begin();
    digitdisplay.displayNumber(); //Numbers from 0-9
    digitdisplay.clearDisplay();

There are more functions in this library which were created for the [il2p-project](https://github.com/ClarkLiam/il2p), which this library was written for.

## Wireing:
Pin1: Top </br>
Pin2: TopRight </br>
Pin3: BottomRight </br>
Pin4: Bottom </br>
Pin5: BottomLeft </br>
Pin6: TopLeft </br>
Pin7: Center
