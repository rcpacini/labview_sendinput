# labview_sendinput
Synthesizes keystrokes using Windows `user32.dll:SendInput` wrapper

## Overview
LabVIEW wrapper for `user32.dll:SendInput` method to synthesizes keystrokes. This is usefull for progromatically testing user interfaces and text entry forms within LabVIEW. 

This library also includes converters for [Virtual Key Codes](https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes) from printable keyboard characters or Windows modifiers (i.e. Shift, Ctrl, Alt).

Refer to Windows Documentaiton on [user32.dll:SendInput](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-sendinput) for more information

## Example
Open and run the `SendInput.llb/_SendInput Keyboard Example.vi`
