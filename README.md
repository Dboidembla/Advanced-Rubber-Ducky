# Advanced-Rubber-Ducky
It is a file which contains up to 13 codes, which are all a proof of concept that means what all attacks rubber ducky can initially perform
Material required:
    •	Arduino pro micro
    •	Usb micro cable
    •	SD card Arduino reader
    •	Jumper cables
    •	Dip switch
Connections to be made:
  •	Ground one side of the dipswitches
  •	Connect rest of pins to the pins pin numbers 6,7,8,9
  •	Now take the Arduino card reader and make the following connections:
      o	Arduino Pro Micro 		SD Card Reader
      o	VCC   				        VCC
      o	GND				            GND
      o	D4				            CS
      o	D14				            MISO
      o	D15				            SCK
      o	D16				            MOSI
  •	Now put the code for Arduino in the pro micro (Code mentioned in the repository)
  •	Now put the designed codes which are in ducky language in the SD Card(Also mentioned in the repository)
  •	Now with different dip switches different codes will work
      o	S. No	  Code Number	  Name of Project
      o	1	      0000		      Ground State
      o	2	      0001		      Initialize Backdoor
      o	3	      0010		      Remove Backdoor
      o	4	      0011		      Disable Firewall and Windows Defender
      o	5	      0100		      Key Logger (only for windows 7)
      o	6	      0101		      Wi-Fi Password Grabber 
      o	7	      0110		      Download Lazagne 
      o	8	      0111		      Execute Lazagne 
      o	9	      1000		      Fake Windows Update 
      o	10	    1001		      Reverse Shell 
      o	11	    1010		      System Hang 
      o	12	    1011		      Lower UAC Value 
      o	13	    1100		      Increase UAC Value 
      o	14	    1101		      Clear Logs
      o	15	    1110
      o	16	    1111
