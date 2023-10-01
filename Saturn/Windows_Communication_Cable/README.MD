# Windows Communication Cable (Windows通信ケーブル)
This cable comes bundled with GAME BASIC for SEGA SATURN.<br>
The cable plugs into the Saturn's Communications port at one end and into a Window computer's RS232 serial port on the other end.<br>
It uses an NEC D4711B RS-232 line driver/receiver to handle the communications between the Saturn and the Windows machine.<br>

## Windows RS232
On the Windows side it uses wires plus shield (シールド):<br>
- red (アカ) wire connected to pin 2 (RS232 Transmit) and 
- white (シロ) wire connected to pin 3 (RS232 Receive).<br>

## Sega Saturn Communication Port (looking at cable)
I don't know if this is the "official" pinout, but I read that the angled corner is supposed to indicate pin 11/12 and odd-on-top, even-on-bottom.  So this is what I've used.<br>
On the Saturn side it uses three wires plus shield (シールド):<br>
- red (アカ) to pin 2
- white (シロ) to pin 5
- black (クロ) to pin 6
'''
   11          1<br>
 ________________<br>
/  | | | | | | | |<br>
|_|_|_|_|_|_|_|__|<br>
 12           2<br>
 '''