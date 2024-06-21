<p align="center"> <a href="https://github.com/Aakif-Kohari/Elliot">
  <img src="https://github.com/Aakif-Kohari/Elliot/assets/159609181/c644130b-9eb9-4642-a201-33ec562f0a7b" alt="Elliot" width="200" height="200">
</p>

# Elliot
Elliot is a basic text editor made using C.
It runs on the command line/terminal.

I made it on a Linux (Ubuntu) Operating System and it runs fine.
On Windows, it shows missing header files and I have yet to find a way to fix that.

Though the code may be similar to `kilo.c` mentioned in the credits I plan to add some stuff. 

## Features
- Can open a file or create a new one.
- Can Save a file with Ctrl-S
- Has Syntax Highlighting for Numbers and Keywords of C language.
- Can quit with Ctrl-Q and is prompted to press it 3 more times if the file is not saved.
- Shows the name of the file and the number of lines in it.
- Shows if the file is Modified.
- Can use Ctrl-F to Find text in the file.

## TO DO
- [ ] Add syntax highlighting rules for common functions in C like printf, scanf, etc.
- [ ] Display the line number to the left of each line.
- [ ] When starting a new line, indent it to the same level as the previous line.
- [ ] Give the user a way to select text and copy the selected text when they press Ctrl-C, and let them paste the copied text when they press Ctrl-V.
- Except these, I may add syntax highlighting for other languages.
## How to Use 
To use the text editor compile and run the `elliot.c` file.
This repository also contains a `Makefile`, an `example.c` file made using this editor and an output file of the code `elliot`. 

## Credit
I made this text editor as a project by following a tutorial 
[**_kilo.c_**](https://viewsourcecode.org/snaptoken/kilo/index.html) .
The source repository of this tutorial is [**_Repository_**](https://github.com/snaptoken/kilo-src/tree/master).

P.S. If I need some Licensing then please show me what to do.
