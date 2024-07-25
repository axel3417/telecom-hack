# telecom-hack
this is my project for hacking a telecom ADSL2+ Wi-Fi N Modem from Technicolor 
Have fun replying it!

bottom cover
![3](https://github.com/user-attachments/assets/3138abf7-c5fa-4983-afd9-a24003660f4c)

top cover
![2](https://github.com/user-attachments/assets/2669c30b-7a03-420a-b299-062e10ed9d4c)

# 1 Serial pin

in the blue circle sits the eeprom that i have desolder it for a chip off extraction because i have killed the serial connection.
For the serial connection you have to short R63 an R62. the second pad from the square one is the GND the third pad should be RX and the last pad should be TX.
![Immagine WhatsApp 2024-07-25 ore 17 10 52_34a988b6](https://github.com/user-attachments/assets/a75db18a-a981-47bd-b57a-c96279602801)


# 2 chip off extraction 
For this you have to desolder the 16 pin chip that sit in the blue circled area.
You can do it with a hot air gun or like I did with a solder iron, solder wick and some solder paste.
Then you have to resolder it on a CH341 eeprom programmer and put the circle of the chip on the pin "1" and inset it in the 25 series chip slot.

then you can read it with the CH341 official software and save the file as BIN.
In the file BIN you will find the linux filesystem


# flash CFW (coming soon)
