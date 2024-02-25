# crackme

An archive of [crackmes](https://crackmes.one) I've solved!

*From [Wikipedia](https://en.wikipedia.org/wiki/Crackme)*:\
*A crackme is a small program designed to test a programmer's [reverse engineering](https://en.wikipedia.org/wiki/Reverse_engineering) skills. They are programmed by other reversers as a legal way to crack software, since no intellectual property is being infringed upon.*


## List (newer to older)
|**date solved** *mm/dd/yyyy*|**crackme name and link**|**coded in:**|**software used**|**brief steps**|**solution**|
|      :-------------        |      :-------------:    |          :---:      |      :---:       |   :-----:    |    ---:    |
|-|-|-|-|-|-|
|02/25/2024|[M4st4rCr4ck's H1dd4n Fl4g](https://crackmes.one/crackme/65a172f0eef082e477ff5a6e)|**C/C++**|![ghidra](https://github.com/creatorpanda/crackme/blob/main/pictures/Ghidra_logo.png)|happened to find the function that prints the flag message, but not a way to actually trigger it|[+] FLAG{B3ST_R3V3RS3R}|
|02/25/2024|[Nalxe's Christmas CrackMe](https://crackmes.one/crackme/6588b4dc35240bf986f106fd)|**C/C++**|![ghidra](https://github.com/creatorpanda/crackme/blob/main/pictures/Ghidra_logo.png)|converted 0xee4 to dec|3812|
|12/28/2022|[CrackMe #2 - register me in your name](https://crackmes.one/crackme/5e49547033c5d4439bb2db75)|**C/C++**|![x96dbg](https://github.com/creatorpanda/crackme/blob/main/pictures/x96dbg_logo.png)|noticed that that the program was trying to read data from a text file named "keyfile"|*created a text file named "keyfile" on the same folder as the .exe was running. the registered name must be written in it.*|
|12/28/2022|[CrackMe1](https://crackmes.one/crackme/6086bfb633c5d458ce0ec6cb)|**C/C++**|![x96dbg](https://github.com/creatorpanda/crackme/blob/main/pictures/x96dbg_logo.png)|backtracked from the wrong serial messagebox.|*CTF{9110-2324-0502-2034-3454}*|
|12/28/2022|[StupidCrackMe](https://crackmes.one/crackme/5c6fb03b33c5d4776a837d14)|**C/C++**|![x96dbg](https://github.com/creatorpanda/crackme/blob/main/pictures/x96dbg_logo.png) & ![ghidra](https://github.com/creatorpanda/crackme/blob/main/pictures/Ghidra_logo.png)|strcmp function comparing user input to global string in main.|*LiL2281337*|
|12/20/2022|[rootAhmed](https://crackmes.one/crackme/639e0c7e33c5d43ab4eceff7)|**.NET**|![ghidra](https://github.com/creatorpanda/crackme/blob/main/pictures/Ghidra_logo.png)|On the Listing window, the u"JSX#SZ@!F&8@Cc%h3@!" line can be easily located at the end of the assembly user imput check.|*JSX#SZ@!F&8@Cc%h3@!*|
|12/20/2022|[Crack Me With Ui.](https://crackmes.one/crackme/628ab7af33c5d45b75903ab4)|**.NET**|![ghidra](https://github.com/creatorpanda/crackme/blob/main/pictures/Ghidra_logo.png)|same as above, but funnier. lel..|*8103535*|
|12/20/2022|[whoami](https://crackmes.one/crackme/5f07485e33c5d42a7c66794d)|**C/C++**|![ghidra](https://github.com/creatorpanda/crackme/blob/main/pictures/Ghidra_logo.png)|located solution string in the Listing window.|*Dad*|
|12/12/2022|[easiest crackme you can find.](https://crackmes.one/crackme/6346ef0933c5d4425e2cd843)|**C/C++**|![ghidra](https://github.com/creatorpanda/crackme/blob/main/pictures/Ghidra_logo.png)|most basic stuff happening with a bit of hexa translation.|*1234*|
