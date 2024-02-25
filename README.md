# Numworks-Chess
A chess game in python for the numworks calculator

DEVELOPMENT IS NOT FINISHED !

## Installation
You can load the script on your calculator from the [script on numworks site](https://my.numworks.com/python/iskandar/chess).

Some browsers don't support WebUSB (which is used by numworks for loading on the calculator) as Firefox or Safari.
You can find [here](https://caniuse.com/webusb) the browsers that provide this api.

#### Info
> If the file is too large for the calculator, try to "obfuscate" the code (change the name of variables, func, etc).

## Emulation
You can emulate the script on your computer by installing the [kandinsky](https://github.com/ZetaMap/Kandinsky-Numworks) and [ion-numworks](https://github.com/ZetaMap/Ion-numworks) python modules (module which are initally native numworks modules for graphics and keyboard input on the calculator).
```bash
pip install kandinsky ion-numworks # or equivalent on your os
```
You can consider using a python env (venv per example).

## Contribution
This is a one-file project because we won't load multiple files for one game on the calculator.
This is not a POO project because I think it would need too much memory for the calculator (so yeah unfortunately it's spaghetti code).

### Progress tree
- [x] Basic moves
- [x] Advanced moves
  - [x] En passant
  - [ ] Castle
  - [ ] Pawn promotion
- [ ] Others
  - [x] Attacking detection
  - [ ] Check system - On going
