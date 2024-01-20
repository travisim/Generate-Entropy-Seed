# **G**enerate **Y**our **O**wn **E**ntropy **S**eed

This project permits to generate your own **BIP39 seed** of 256 bit, by inputting any number(From 0-9) and using random variance to generate the rest of the numbers. So that you don't have to trust any organisation to track the random seed you used to generate your mnemonic.

This is a python script that accepts as a parameter a string of decimals created with your own entropy and generates a bip39 mnemonic seed.


## Usage example:
Download the project as a zip, open a terminal in the directory and type:

```
python3 main.py
```

then follow the script instructions.

## Don't trust, verify!
The code is very minimal and simple so that can be reviewed. In order to avoid that you have to review the bip39 words list, it is in a separate file and you can just delete that one and download it again from https://raw.githubusercontent.com/bitcoin/bips/master/bip-0039/english.txt and save it as `english.txt`


## Disclaimer:
Use this project at your own risk. 

I DON'T have any responsability of how you will use it and eventual money loss.

Don't use this project for your actual wallet if you don't know what you are doing!!
