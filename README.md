# MEGA-JVS
Jamma Video Standard (JVS) IO board implemented using a MEGA 2560

The included Arduino code is intended to be used with a MEGA 2560 and a MEGA JVS V2 board (created by winteriscoming).  The boards are currently not available for sale.

The MEGA JVS V2 board has a micro SD slot.  Profiles are stored on the card.  The directory called SD Card Contents needs to go in the root of the Micro SD card.  This includes both PROFILES.HEX and LASTPROF.HEX.

In order to create more mapping profiles and edit existing ones, use profiles.py and open PROFILES.HEX from the micro SD card.

The use of profiles.py is not well documented yet.

The MEGA JVS V2 board uses a profile button to switch profiles on-the-fly.  It also uses a small OLED display like the one found here: https://www.amazon.com/Display-Serial-Arduino-Raspberry-DIYmall/dp/B073VD6W1H/ref=sr_1_1?ie=UTF8&qid=1533843988&sr=8-1&keywords=oled+diymall