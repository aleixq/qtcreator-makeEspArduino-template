# Qt Creator esp8266 wizard
A wizard for intergrating embeded ESP8266 modules into QtCreator using Arduino style setup loop thing.
Modified from https://github.com/jontio/qt_esp8266_wizard.

## About template
This repository creates a template that you allows you to configure Qt Creator as your Arduino's IDE.
* [Qtcreator](https://en.wikipedia.org/wiki/Qt_Creator)
* [makeEspArduino](https://github.com/plerup/makeEspArduino)
* [esp8266/Arduino](https://github.com/esp8266/Arduino)
* [Perl](https://en.wikipedia.org/wiki/Perl)
* Serial monitor (for example GTKTerm version > 0.99 or picocom, or screen or minicom)

## Boards supported and tested
Theoretically this template can support all boards that https://github.com/plerup/makeEspArduino support.

## How to install
In this repository you will find these templates in folders:
* esp8266
  + This directory contains an Arduino Sketch Style for Esp8266 devices. 
  + It also has a default configuration that will fill the *Build* step in run configuration as `make flash`.
  + and will fill the *Run* > run configuration to run the Serial monitor software defined in wizard.
  + To allow providing the default settings by wizard, the kit id must be defined in wizard, it's in `~/.config/QtProject/qtcreator/profiles.xml` (sorry, no automatic discover is possible).

1) Clone this repo as advised in http://doc.qt.io/qtcreator/creator-project-wizards.html.
2) Click on:
File > New File or Project
Select AVR > ESP8266

INSTALLATION INSTRUCTIONS
-------------------------

1) Clone this repo as advised in http://doc.qt.io/qtcreator/creator-project-wizards.html.

2) Click on:
File > New File or Project
Select AVR > Arduino project using sketch.

## Based on work of: 
* https://github.com/jontio/qt_esp8266_wizard/
