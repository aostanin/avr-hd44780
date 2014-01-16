# avr-hd44780

## Description

This is an avr-gcc library for the HD44780 character LCD display.

After buying the SC1602BS LCD module, I couldn't find an avr-gcc library that drives the display correctly. Arduino's LiquidCrystal library was the only library that worked so this is a simple avr-gcc version of that library.

Tested with the Teensy++ 2.0 development board.

## Usage

See `lcd.h` for the usable methods. You need to edit it with the pins you're using.

## License

Licensed under the GNU General Public License, Version 2.0.

You may find a copy of the license at

```
http://www.gnu.org/licenses/gpl-2.0.html
```

## References

- [SC1602BS Character Display Module](http://akizukidenshi.com/catalog/g/gP-00040/)
- [Arduino's LiquidCrystal library source](https://code.google.com/p/arduino/source/browse/trunk/libraries/LiquidCrystal)
