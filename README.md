# labview_sendinput
Synthesizes keystrokes and mouse clicks using Windows `user32.dll`.

## Overview
LabVIEW wrapper to send keystrokes and mouse events programatically using 
Windows `user32.dll:sendinput()`, `user32.dll:SetCursorPos()` and `user32.dll:mouse_event()`.

This is useful to programatically testing user interfaces and text entry forms within LabVIEW. 

## Additional Information

This library also includes converters 
for [Virtual Key Codes](https://docs.microsoft.com/en-us/windows/win32/inputdev/virtual-key-codes) 
from printable keyboard characters or Windows modifiers (i.e. Shift, Ctrl, Alt).

Refer to Windows Documentaiton 
on [user32.dll:SendInput](https://docs.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-sendinput) 
for more information

## Example
Open and run the `SendInput.llb\_SendInput Keyboard Example.vi`
