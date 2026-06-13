# Electronic Components used by RaspiPCB

## Buck Converters

| Part                                                       | Description             | Input Voltage | Output Current | Quiescent Current | Example Design                              |
| ---------------------------------------------------------- | ----------------------- | ------------- | -------------- | ----------------- | ------------------------------------------- |
| [TPS62086](https://www.ti.com/lit/ds/symlink/tps62085.pdf) | 3-A Step-Down Converter | 2.5V ~ 6.0V   | 3A             | 17uA              | *akshayylr* 3.5 ~ 5.5V input 3.3V 1A output |

## Boost Converters

| Part                                                       | Description                                            | Input Voltage | Output Current | Quiescent Current | Example Design                       |
| ---------------------------------------------------------- | ------------------------------------------------------ | ------------- | -------------- | ----------------- | ------------------------------------ |
| [TPS61288](https://www.ti.com/lit/ds/symlink/tps61288.pdf) | 18-V 15-A Fully Integrated Synchronous Boost Converter | 2.0V ~ 18V    | 15A            | 110uA             | *air6systems* 14V 2A boost converter |

## Buck-Boost Converters

| Part                                                         | Description                                    | Input Voltage | Output Current | Quiescent Current | Example Design                           |
| ------------------------------------------------------------ | ---------------------------------------------- | ------------- | -------------- | ----------------- | ---------------------------------------- |
| [TPS552892](https://www.ti.com/lit/ds/symlink/tps552892.pdf) | 36-V 8-A Fully Integrated Buck-boost Converter | 3.0V ~ 36V    | 8A             | 760uA             | alexanderhoerl 4 ~ 8V input 5V 4A output |

## LDO, Ideal Diodes

| Part                                                     | Description                                       | Input Voltage | Output Current | Quiescent Current | Example Design |
| -------------------------------------------------------- | ------------------------------------------------- | ------------- | -------------- | ----------------- | -------------- |
| [TLV704](https://www.ti.com/lit/ds/symlink/tlv704.pdf)   | 24V 150-mA 3.2-μA Quiescent Current LDO           | 2.5V ~ 24V    | 150mA          | 3.2uA             | -              |
| [LM66200](https://www.ti.com/lit/ds/symlink/lm66200.pdf) | 1.6 V to 5 V 2.5-A Dual Ideal Diode               | 1.6V ~ 5.5V   | 2.5A           | 1.32uA            | -              |
| [LM73100](https://www.ti.com/lit/ds/symlink/lm66200.pdf) | 28mΩ 5.5A load switch with integrated ideal diode | 2.7V ~ 23V    | 5.5A           | 190uA             | aitelemetry    |

## Load Switches

| Part                                                          | Description                                               | Input Voltage | Output Current | Quiescent Current | Example Design     |
| ------------------------------------------------------------- | --------------------------------------------------------- | ------------- | -------------- | ----------------- | ------------------ |
| [TLV704](https://www.ti.com/lit/ds/symlink/tlv704.pdf)        | 24V 150-mA 3.2-μA Quiescent Current LDO                   | 2.5V ~ 24V    | 150mA          | 3.2uA             | -                  |
| [LM66200](https://www.ti.com/lit/ds/symlink/lm66200.pdf)      | 1.6 V to 5 V 2.5-A Dual Ideal Diode                       | 1.6V ~ 5.5V   | 2.5A           | 1.32uA            | -                  |
| [TPS22917](https://www.ti.com/lit/ds/symlink/tps22917.pdf)    | 5.5V 2A 80mΩ Ultra-Low Leakage Load Switch                | 1V ~ 5.5V     | 2A             | 0.5uA             | instantasset-rfm   |
| [TPS22995](https://www.ti.com/lit/ds/symlink/tps22995.pdf)    | 3.8A 18mΩ On-Resistance Load Switch                       | 1.5V ~ 5.5V   | 3.8A           | 10uA              | akshayylr          |
| [TPS22997](https://www.ti.com/lit/ds/symlink/tps22997.pdf)    | 5.5V 10A 4mΩ On-Resistance Load Switch                    | 1.5V ~ 5.5V   | 10A            | 10uA              | elesenseno-ups     |
| [TPS25961](https://www.ti.com/lit/ds/symlink/tps25961.pdf)    | 2.7V–19V 106mΩ eFuse With Adjustable Current Limit        | 2.7V ~ 19V    | 2A             | 130uA             | habot_it           |
| [TPS1HC30](https://www.ti.com/lit/ds/symlink/lm7310.pdf) | 30mΩ 5-A Single-Channel Automotive Smart High Side Switch | 3.5V ~ 18V    | 5A             | 1.6mA             | maiakhoa-leddriver |

## Raspberry Pi CM4 / CM5 Connectors

| Part                        |  Manufacturer |  Description                               |  Height from PCB |
| --------------------------- | ------------- | ------------------------------------------ | ---------------- |
| DF40HC(3.0)-100DS-0.4V(51)  |  Hirose       |  Recommended by Raspberry Pi CM4 Datasheet |  3mm             |
| LBF29-G100S-B0R01           |  LXWCONN      |                                            |  3mm             |
| HC-PBB40C-100DS-0.4V-3.0-02 |  HCTL         |                                            |  3mm             |
| 10164227-1004A1RLF          |  Amphenol     |  Recommended by Raspberry Pi CM5 Datasheet |  4mm             |
