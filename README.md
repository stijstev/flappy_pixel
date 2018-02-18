# FlappyPixel v1.0.0

My first Python project. A fun little game for your Raspberry Pi w/ SenseHAT

## Author

**Stijn Stevens** - [StijStev](https://github.com/stijstev)

Like this project? Support the creator! It's always appreciated :)
* Ethereum address: 0x16A49febDe0c927BC942878e644ea35a18dcF6CF

## Features

* Move the pixel through the oncomming walls
* 5 difficulties to choose from
* Support for onboard joystick and Xbox 360 Controller
* Increasing the difficulty will also increase the score per wall!

## Requirements

* Raspberry Pi (3)
* SenseHAT

## How to play

1. Open the terminal (Skip this step if your Pi boots into the command line straight away)
2. Clone this repository to a directory of your desire
3. Enter following command: 

```shell
> python FlappyPixel.pyc --scheme < 'joy' for onboard joystick, 'xbox' for xbox 360 controller> --diff < int between 1 and 5 >
```

Move your Pixel with either the onboard joystick or the dpad on your 360 Controller
Press joystick down to quit, or press 'a' to quit.

## Known bugs

* Program may occasionally launch again after quiting. If you know what causes this, please message me.
* Using the Xbox 360 Controller makes the game run really slow. If you know what causes this, please message me.
* No console warning when no arguments are passed. That's what I get for using getopt.

Tested with Raspberry Pi 3 with Raspbian

## FAQ

Q: Why are there no keyboard controls?
A: Because I'm a keyboard racist.

That's it really. I don't anticipate too many frequently asked questions.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details






