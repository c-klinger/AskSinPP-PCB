# AskSin++ PSB
Collection of my PCBs for building Homebrew devices using [AskSin++](https://github.com/pa-pa/AskSinPP).

## HB-UNI-328P
soon...

## HB-UNI-328P-SMALL
Flexible and small (49x49mm) PCB for AskSin++ devices with multiple power options. Small enough to fit into devices that integrate into german wall socket / switch series.

![PCB Picture](https://raw.githubusercontent.com/c-klinger/AskSinPP-PCB/main/hb-uni-328p-small/images/hb-uni-328p-small-pcbs.jpg)

[Schematics](https://github.com/c-klinger/AskSinPP-PCB/blob/main/hb-uni-328p-small/hb-uni-328p-small.pdf)

### Bill of Material

| Pos | References | Description | Value | Size | Quantity | Order Links \* | Notes |
|-----|------------|-------------|-------|------|----------|-------------|-------|
| 01 | U1 | ATmega328P(B) |  | TQFP-32 | 1 | [Reichelt](https://www.reichelt.de/8-bit-atmega-avr-mikrocontroller-32-kb-20-mhz-tqfp-32-atmega-328pb-au-p269093.html), [Aliexpress](https://s.click.aliexpress.com/e/_DmFgvzj) | |
| 02 | U2 | CC1101 Module |  |  | 1 | [Aliexpress](https://s.click.aliexpress.com/e/_DnFmipB) | |
| 03 | U3 | MAX1724EZK33 | | SOT-23 | 1 | [Mouser](https://www.mouser.de/ProductDetail/Analog-Devices-Maxim-Integrated/MAX1724EZK33%2bT?qs=1THa7WoU59ExxSPMjwY5Kw%3D%3D),  [Aliexpress](https://s.click.aliexpress.com/e/_DEjlEQt) | Only for Poweroption 1
| 04 | U4 | HT7533 | | SOT-89 | 1 | [ELV](https://de.elv.com/spannungsregler-33v-ht-7533-1-smd-sot-89-056535),  [Aliexpress](https://s.click.aliexpress.com/e/_Dkyk1p7)  | Only for Poweroption 2
| 05 | Q1 | IRLML6244 | | SOT-23 | 1 | [Reichelt](https://www.reichelt.de/mosfet-n-kanal-20-v-6-3-a-rds-on-0-021-ohm-sot-23-irlml-6244-p132145.html), [Aliexpress](https://s.click.aliexpress.com/e/_DmmdQxj) | only for Poweroption 1 
| 06 | Q2 | IRLML5203 | | SOT-23 | 1 | [Reichelt](https://www.reichelt.de/mosfet-p-kanal-30-v-3-a-rds-on-0-098-ohm-sot-23-irlml-5203-p108740.html), [Aliexpress](https://s.click.aliexpress.com/e/_DmmdQxj) | only for Poweroption 2 
| 07 | C1, C6, C8, C10, C11 | Capacitor | 10uF | 1206 | 4 (max) | [Reichelt](https://www.reichelt.de/ch/de/vielschicht-kerko-10-f-16v-125-c-kem-x7r1206-10u-p207163.html),  [Aliexpress](https://s.click.aliexpress.com/e/_DCrWg7b) | C8 for Poweroption 1, C10 + C11 for Poweroption 2
| 08 | C2, C7, C5 | Capacitor | 100nF | 1206 | 3 | [Reichelt](https://www.reichelt.de/smd-vielschicht-keramikkondensator-100n-10--x7r-g1206-100n-p22889.html),  [Aliexpress](https://s.click.aliexpress.com/e/_DCrWg7b) | |
| 09 | C3, C4 | Capacitor | 9-12pF | 1206 | 2 | [Reichelt](https://www.reichelt.de/vielschicht-kerko-1206-10-pf-5-cog-50-v-125-c-ve-4k-npo-g1206-10p-p31885.html), [Aliexpress](https://s.click.aliexpress.com/e/_DCrWg7b) | |
| 10 | C9  | Capacitor | 33nF | 1206 | 1 | [Reichelt](https://www.reichelt.de/smd-vielschicht-keramikkondensator-33n-10--x7r-g1206-33n-p22890.html), [Aliexpress](https://s.click.aliexpress.com/e/_DCrWg7b) | only for Poweroption 1 |
| 11 | C12  | Electrolytic Capacitor | 1000uF |  | 1 | [Reichelt](https://www.reichelt.de/elko-1000-f-50v-105-c-rad-lxz-50-1k0-p166432.html), [Aliexpress](https://s.click.aliexpress.com/e/_DCrWg7b) | only for Poweroption 2 |
| 12 | C13  | Capacitor | 10nF | 1206 | 1 | [Reichelt](https://www.reichelt.de/vielschicht-kerko-1206-10-nf-10-x7r-50-v-125-c-x7r-g1206-10n-p31897.html), [Aliexpress](https://s.click.aliexpress.com/e/_DCrWg7b) |  | 
| 13 | D1 | Dual LED | | 3mm | 1 | [Reichelt](https://www.reichelt.de/ch/de/led-3-mm-tht-3-pin-rot-gruen-627-565-nm-40-40-mcd-60--kbt-l-115wegw-p231039.html), [Aliexpress](https://s.click.aliexpress.com/e/_DFd0iCd) |  |
| 14 | F1 | Fuse (PTC) | 6V, 250mA | 1206 | 1 | [Aliexpress](https://s.click.aliexpress.com/e/_DEQvumh) | for Poweroption 1 |
|    | F1 | Fuse (PTC) | 16V, 250mA | 1206 | 1 | [Reichelt](https://www.reichelt.de/ptc-sicherung-smd-1206-16v-350ma-rueckstellend-ptc-fsmd0351206--p279338.html), [Aliexpress](https://s.click.aliexpress.com/e/_DEQvumh) | for Poweroption 2 |
| 15 | J3 | Pin Header 2.54mm |  | 2x1 | 1 | [Reichelt](https://www.reichelt.de/ch/de/stiftleisten-2-54-mm-1x02-gerade-mpe-087-1-002-p119879.html), [Aliexpress](https://s.click.aliexpress.com/e/_Dl2TPCt) | optional |
| 16 | J4 | Pin Header 2.54mm |  | 6x1 | 1 | [Reichelt](https://www.reichelt.de/ch/de/stiftleisten-2-54-mm-1x06-gerade-mpe-087-1-006-p119883.html), [Aliexpress](https://s.click.aliexpress.com/e/_Dl2TPCt) | optional |
| 17 | J5 | Pin Header 2.54mm |  | 3x2 | 1 | [Reichelt](https://www.reichelt.de/ch/de/stiftleisten-2-54-mm-2x03-gerade-mpe-087-2-006-p119893.html), [Aliexpress](https://s.click.aliexpress.com/e/_DFoS9I5) | optional |
| 18 | J6 | Pin Header 2.54mm |  | 4x1 | 1 | [Reichelt](https://www.reichelt.de/ch/de/stiftleisten-2-54-mm-1x04-gerade-mpe-087-1-004-p119881.html), [Aliexpress](https://s.click.aliexpress.com/e/_Dl2TPCt) | optional|
| 19 | L1 | Induction Coil | 10UH | 4x3mm| 1| [Conrad](https://www.conrad.de/de/p/murata-lqh43cn100k03l-lqh43cn100k03l-induktivitaet-smd-1812-10-h-0-65-a-1-st-537082.html) [Aliexpress](https://s.click.aliexpress.com/e/_DFXlwZn) |only for Poweroption 1 |
| 10 | R1, R2 | Resistor | 330 | 1206 | 2 | [Richelt](https://www.reichelt.de/ch/de/smd-widerstand-1206-330-ohm-250-mw-1--vis-crcw1206330-p238114.html), [Aliexpress](https://s.click.aliexpress.com/e/_DDa77BX) |  |
| 21 | R3, R8, R9 | Resistor | 10K | 1206 | 3 | [Reichelt](https://www.reichelt.de/ch/de/smd-widerstand-1206-10-kohm-250-mw-5--smd-1-4w-10k-p18244.html) [Aliexpress](https://s.click.aliexpress.com/e/_DDa77BX) |  |
| 22 | R4 | Resistor | 470K | 1206 | 1 | [Reichelt](https://www.reichelt.de/ch/de/smd-widerstand-1206-470-kohm-250-mw-5--smd-1-4w-470k-p18338.html), [Aliexpress](https://s.click.aliexpress.com/e/_DDa77BX) |  |
| 23 | R5, R6, R7 | Resistor | 100K | 1206 | 3 (max) | [Reichelt](https://www.reichelt.de/ch/de/smd-widerstand-1206-100-kohm-250-mw-5--smd-1-4w-100k-p18243.html), [Aliexpress](https://s.click.aliexpress.com/e/_DDa77BX) | R7 for Poweroption 2 only |
| 24 | SW1, SW2 | Tactile Switch | | 6x3mm | 2 | [Aliexpress](https://s.click.aliexpress.com/e/_DlZyH0Z) | |
| 25 | Y1 |  SMD Crystal | 32.768 KHz | 3.8x8mm | 1 | [Reichelt](https://www.reichelt.de/ch/de/keramik-smd-quarz-8-7-x-3-7-x-2-5-mm-32-768-khz-iqd-lfxtal003000-p245481.html), [Aliexpress](https://s.click.aliexpress.com/e/_Dn3q3Az) | |

\* *I have not tested all parts using this order links, no guarantee that every linked component works. Aliexpress links are affiliate links, so i will get a small commission when you order using this link. This will help me with further projects. Thanks.*

### Comments
* Minimum size of SMD components is 1206: it's possible to solder the PCB by hand.
* 3 Power Options
    * Poweroption 1: Step-Up DC-DC Converter MAX1724EZK33: 0.8V to 5.5V Input Voltage Range. Best for Battery powered devices.
    * Poweroption 2: Linear Voltage Regulators (LDO) HT7533: 5-12V Input Voltage Range. Best for most external DC Power Supply. Jumper J2 needs to be shortened for this Poweroption. 
    * Poweroption 3: External 3.3V Supply. Jumper J1 and J2 needs to be shortened this Poweroption. No fuse or reverse polarity protection!
* Assembly and use only one of the Power Options at time.

Inspired from pa-pa [HMSensor](https://github.com/pa-pa/HMSensor) and [HB-UNI-644](https://github.com/alexreinert/PCB#hb-uni-644-rev-2) from alexreinert. Thanks for your work.

# LICENSE
[![Creative Commons Lizenzvertrag](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

All content in this repository is is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license](https://creativecommons.org/licenses/by-nc-sa/4.0/).

