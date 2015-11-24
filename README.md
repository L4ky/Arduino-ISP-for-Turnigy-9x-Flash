# Arduino-ISP-for-Turnigy-9x-Flash
Arduino ISP for flashing Turnigy 9x radio

Why use this?

Because there's a problem when calculating the address while reading/writing the EEPROM.
When you try to backup/restore models using OpenTX Companion you will get a corrupted EEPROM message.
That's not true! Load this sketch on your Arduino and it will work.
NOTE: I tested and used this on Arduino Mega 2560.

When flashing the firmware everything works fine!

I found the fix online, i can't remember which website. I will post it here when i will find it again.
