# Floppy Disk Controller for 65C02 system
This is a floppy disk controller board for my homebrew 65C02 based system

Make sure to program the ATF16V8 with the .JED file contained within the PLD folder before soldering to the board

![PCB Top](Images/top.png?raw=True)
![PCB Bottom](Images/bottom.png?raw=True)

## Bill of materials
|Component|Designator|QTY|Link|
|---------|--------|---|------|
|82077AA or PC8477B|U1|1|eBay|
|ATF16V8 PLD|U2|1|[Mouser](https://www.mouser.com/ProductDetail/556-AF16V8B15PU)|
|PLCC-68 Socket|U1|1|[Mouser](https://www.mouser.com/ProductDetail/575-1104732041001000)|
|20-pin DIP socket|U2|1|[Mouser](https://www.mouser.com/ProductDetail/517-8468-11B1-RK-TP)|
|40-Pin IDC Header|CON1|1|[Mouser](https://www.mouser.com/ProductDetail/517-N2524-6002RB)|
|4.7nF Ceramic Capacitor (Not needed for PC8477)|C1|1|[Mouser](https://www.mouser.com/ProductDetail/810-FA18X7R2A47200)|
|0.1uF Ceramic Capaictor|C2-7|6|[Mouser](https://www.mouser.com/ProductDetail/594-K104K15X7RF53H5)|
|100uF Electrolytic Capacitor|C8|1|[Mouser](https://www.mouser.com/ProductDetail/667-ECA-1AM101I)|
|Resistor network - Bussed, 1K 6 pin|RN1|1|[Mouser](https://www.mouser.com/ProductDetail/652-4606M-1LF-1K)|
|24MHz Can Oscillator|X1|1|[Mouser](https://www.mouser.com/ProductDetail/520-2200B-240)|