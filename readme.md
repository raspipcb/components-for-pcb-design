# Electronic Components used by RaspiPCB

## Power Supply and Power Distribution ICs

| Part                                                       |  Description                                            |  Input Voltage |  Output Current |  Quiescent Current |  Example Design                              |
| ---------------------------------------------------------- | ------------------------------------------------------- | -------------- | --------------- | ------------------ | -------------------------------------------- |
| [TPS61288](https://www.ti.com/lit/ds/symlink/tps61288.pdf) |  18-V 15-A Fully Integrated Synchronous Boost Converter |  2.0V ~ 18V    |  15A            |  110uA             |  *air6systems* 14V 2A boost converter        |
| [TPS62086](https://www.ti.com/lit/ds/symlink/tps62085.pdf) |  3-A Step-Down Converter                                |  2.5V ~ 6.0V   |  3A             |  17uA              |  *akshayylr* 3.5 ~ 5.5V input 3.3V 1A output |
| [TLV704](https://www.ti.com/lit/ds/symlink/tlv704.pdf)     |  24-V 150-mA 3.2-μA Quiescent Current LDO               |  2.5V ~ 24V    |  150mA          |  3.2uA             |  -                                           |
| [LM66200](https://www.ti.com/lit/ds/symlink/lm66200.pdf)   |  1.6 V to 5 V 2.5-A Dual Ideal Diode                    |  1.6V ~ 5.5V   |  2.5A           |  1.32uA            |  -                                           |


## Raspberry Pi CM4 / CM5 Connectors

| Part                        |  Manufacturer |  Description                               |  Height from PCB |
| --------------------------- | ------------- | ------------------------------------------ | ---------------- |
| DF40HC(3.0)-100DS-0.4V(51)  |  Hirose       |  Recommended by Raspberry Pi CM4 Datasheet |  3mm             |
| LBF29-G100S-B0R01           |  LXWCONN      |                                            |  3mm             |
| HC-PBB40C-100DS-0.4V-3.0-02 |  HCTL         |                                            |  3mm             |
| 10164227-1004A1RLF          |  Amphenol     |  Recommended by Raspberry Pi CM5 Datasheet |  4mm             |
