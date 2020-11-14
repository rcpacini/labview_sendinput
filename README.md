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

## ASCII
Dec  Char
0 NUL (null)
1 SOH (start of heading)
2 STX (start of text)
3 ETX (end of text)
4 EOT (end of transmission)
5 ENQ (enquiry)
6 ACK (acknowledge)
7 BEL (bell)
8 BS (backspace)
9 TAB (horizontal tab)
10 LF (NL line feed, new line)
11 VT (vertical tab)
12 FF (NP form feed, new page)
13 CR (carriage return)
14 SO (shift out)
15 SI (shift in)
16 DLE (data link escape)
17 DC1 (device control 1)
18 DC2 (device control 2)
19 DC3 (device control 3)
20 DC4 (device control 4)
21 NAK (negative acknowledge)
22 SYN (synchronous idle)
23 ETB (end of trans. block)
24 CAN (cancel)
25 EM (end of medium)
26 SUB (substitute)
27 ESC (escape)
28 FS (file separator)
29 GS (group separator)
30 RS (record separator)
31 US (unit separator)
32 SPACE
33 !
34 "
35 #
36 $
37 %
38 &
39 '
40 (
41 )
42 *
43 +
44 ,
45 -
46 .
47 /
48 0
49 1
50 2
51 3
52 4
53 5
54 6
55 7
56 8
57 9
58 :
59 ;
60 <
61 =
62 >
63 ?
64 @
65 A
66 B
67 C
68 D
69 E
70 F
71 G
72 H
73 I
74 J
75 K
76 L
77 M
78 N
79 O
80 P
81 Q
82 R
83 S
84 T
85 U
86 V
87 W
88 X
89 Y
90 Z
91 [
92 \
93 ]
94 ^
95 _
96 `
97 a
98 b
99 c
100 d
101 e
102 f
103 g
104 h
105 i
106 j
107 k
108 l
109 m
110 n
111 o
112 p
113 q
114 r
115 s
116 t
117 u
118 v
119 w
120 x
121 y
122 z
123 {
124 |
125 }
126 ~
127 DEL
