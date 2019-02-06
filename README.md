# VBA obfuscator
> Final year school project, obfuscate Word macros.

This program obfuscates the Visual Basic code from Microsoft Word macros. 
The transformations applied on the code allows the macros to evade signature scans from Antivirus softwares.

Please do no 
## Usage example

With Docker:

```sh 
cat YOUR_MACRO.vbs | docker run -i --rm bonnetn/vba-obfuscator /dev/stdin
```

This command will obfuscate the whole code. 

:warning: **Pay attention** to the first two lines! 

:warning: It is necessary to add a document variable to the word document before pasting the code.
You can dispose of the first two lines once it has been executed once on the Word document.

## Development setup

Install python3 and the requirements.

> pip install -r requirements.txt

To run the tests:
> pytest

Then run:
> python3 obfuscate.py YOUR_MACRO.vbs
## Authors

Thomas Leroy - thomas.leroy.mp@gmail.com

Nicolas Bonnet – mail@nicolasbon.net

## Demo

[![Demo](https://img.youtube.com/vi/AEkFpD6CHCw/0.jpg)](https://www.youtube.com/watch?v=AEkFpD6CHCw)

[![asciicast](https://asciinema.org/a/5Ptyf5oNGT7xtkZZvnqNDHMml.svg)](https://asciinema.org/a/5Ptyf5oNGT7xtkZZvnqNDHMml)


## Disclaimer
The VBA obfuscator tool is provided for educational and research purposes only. 
The authors of this project are no way responsible for any misuse of this tool.

Do not attempt to violate the law with our project, we will not take any responsability for your actions.
