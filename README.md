# LPT2FDD
LPT to Floppy Drive adapter for supported vintage laptops. This revision is specifically designed for the Sharp PC-9000 / 9030 series laptops but may also work on clones or subsequent Sharp laptops as well. The laptop must support floppy protocol through the LPT port for this to work. This project also serves as an archive for pin sets required for LPT floppy protocols.

<img src='Images/LPT2FDD_photo.JPG' width=480>
<img src='Images/LPT2FDD_schematic.png' width=480>
<img src='Images/LPT2FDD_PC-90XX.JPG' width=480>

v0.5 Adds a jumper resistor between pins 21 and 22 to allow compatibility with Compaq laptop external floppy detection. Currently it is recommended to use a 1k resistor for extra safety. This should trigger the Compaq laptop to recognize a connected floppy drive (if supported by laptop), but external power needs to be provided separately to the floppy drive. 

More information and discussion can be found here - https://www.vogons.org/viewtopic.php?t=105093.
 
## Build of Materials and Installation
Other than the PCB, there are really only two other connectors required to build the LPT2FDD.
Use with a standard single drive floppy cable with the twist. Powering the floppy drive externally is required. A ps/2 to 5v adapter will be provided soon.

Pin 3 of the DC3 connector may need to be removed for keyed floppy cables. 

### Example Sources
34-Pin DC3 Connector
https://www.aliexpress.us/item/3256806835271080.html?spm=a2g0o.order_list.order_list_main.110.1ec5180292mWAN&gatewayAdapt=glo2usa

D-SUB DB-25 Male or Female
https://www.aliexpress.us/item/3256805300852948.html?spm=a2g0o.order_list.order_list_main.121.1ec5180292mWAN&gatewayAdapt=glo2usa

Single Drive Floppy cable
https://www.aliexpress.us/item/3256805300852948.html?spm=a2g0o.order_list.order_list_main.121.1ec5180292mWAN&gatewayAdapt=glo2usa

## Support the Developer
This project is brought to you free and open source, but it is not free to develop. If you like this project please consider supporting this and future developments. 

https://www.patreon.com/RetroLoom