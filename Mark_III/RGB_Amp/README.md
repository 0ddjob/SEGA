# Sega Mark III RGB Amplifier
Internal amplifier board for the Sega Mark III RGB output.<br>

The RGB output is apparently a bit dim so one solution is to use a THS7314D (or similar) video amplifier to boost the output level.<br>

Based on ideas by [にがMSX](http://niga2.sytes.net/msx/mk3.html)<br>

Design uses:<br>
- 6 x 75Ω (0805) resistors
- 1 x 100Ω (0805) resistor
- 1 x 100nF (0805) capacitor
- 1 x THS7314D video amplifier (6dB gain)
- 6-pin header for RGBS+power input
- 5-pin header for RGBS+ground output

![PCB_mockup](Pictures/Sega_MkIII_RGB_Amp_PCB.png)
