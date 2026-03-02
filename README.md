# Identsmart ID500

I got my hands on an outdated ID500 device so I wanted to disassemble it and figure out what was really going on underneath the shell.

# Disassembly
It turns out picking one of these apart is harder than expected. I ended up figuring out that the best option was to go from the bottom where the plastic shell wraps around. Using a little flat screwdriver I slowly went around and levered out the top plastic casing. And after unscrewing some screws the ID500 was already disasembled.

# Discovery
I have to admit that I was shocked when I found out that the display and firmware where all running on a cheap little Android phone. The chip detection is done through a litte NFC/RFID scanner that is connected via USB to the phone. Because that means the charging port is occupied the back cover of the phone was removed and power is supplied by charging the battery directly.

# Specs / Price
These are all the specs:
- Xiaomi REDMI Go: ($80)
    - OS: Android 8.1 Go Edition
    - Chip: Qualcoom Snapdragon 425 MSM8917
    - Battery: Li-Po, 3000.0 mah
    - Display: LCD_IPS 70.1 x 140.4px
    - RAM: 8GB
    - Built in GPS
    - LTE/5G
- USB NFD reader based on an NXP PN532-class NFC controller paired with an NXP LPC11U68 USB microcontroller ($8)
- Lipo charger LP0002497 manufactured by identos ($6.95)

Total cost: ~ $95

Original cost: ~$600

# Gallery
![[./pictures/full.jpg]]
![[./pictures/phone.jpg]]
![[./pictures/nfc.jpg]]
![[./pictures/charger.jpg]]
