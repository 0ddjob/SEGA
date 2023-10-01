# Windows Communication Cable
# Windows通信ケーブル
This cable comes bundled with GAME BASIC for SEGA SATURN.<br>
The cable plugs into the Saturn's Communications port at one end and into a Window computer's RS232 serial port on the other end.<br>
It uses an [NEC D4711B](Documentation/NEC_UPD4711BGS_Datasheet.pdf) RS-232 line driver/receiver to handle the communications between the Saturn and the Windows machine.<br>

![Communications Cable](Pictures/Saturn_Windows_Comm_Cable.jpg)

## Windows RS232
On the Windows side it uses wires plus shield:<br>
- red (アカ) wire connected to pin 2 (RS232 Transmit)
- white (シロ) wire connected to pin 3 (RS232 Receive)
- shield (シールド) wire connected to pin 7 (RS232 signal ground) plus shield

The DE9 cable equivalents would be:<br>
- red (アカ) wire connected to pin 3 (RS232 Transmit)
- white (シロ) wire connected to pin 2 (RS232 Receive)
- shield (シールド) wire connected to pin 5 (RS232 signal ground) plus shield

## Sega Saturn Communication Port (looking at cable)
I don't know if this is the "official" pinout, but I read that the angled corner is supposed to indicate pin 11/12 and odd-on-top, even-on-bottom.  So this is what I've used.<br>
```
   11          1
 _________________
/  | | | | | | | |
|_|_|_|_|_|_|_|__|
 12           2
```
On the Saturn side it uses three wires plus shield:<br>
- red (アカ) to pin 2
- white (シロ) to pin 5
- black (クロ) to pin 6
- shield (シールド) to pins 8 & 12 (plus outside shield)

![Saturn Communications Plug](Pictures/Saturn_Communication_Plug.jpg)
