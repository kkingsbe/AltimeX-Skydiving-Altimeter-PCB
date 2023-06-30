# Open-Source-Skydiving-Altimeter-PCB

This repo contains the PCB files for an open-source ColorAlti analog that I created, which can be made for about $30. Sadly, the programmer cable costs anywhere from $60-$120, however if you need yours programmed you can reach out to me and we can work something out (I have one).

This is still an active work in progress. A LiPo with a capacity of at least 250mAh should be fine since the current draw of the board is minimal. The CAD files for an enclosure that can fit in the audible pocket on helmets will be up soon once tested.

## Bill of Materials
|Part            |Part Number            |Price (per item)|Amount|Link|
|----------------|-----------------------|----------------|------|----|
|MCU             |STM32F103              |$6.66           |1     |[Click Here](https://www.digikey.com/en/products/detail/stmicroelectronics/STM32F103C8T6/1646338)|
|LED Strip       |WS2813B                |$15.00          |1     |[Click Here](https://www.amazon.com/LOAMLIN-Individually-Addressable-144Pixels-Waterproof/dp/B0BDRCQWWQ/ref=sr_1_30_sspa?crid=3CKX9YASAYWQJ&keywords=ws2813b%2Bled%2Bstrip%2Bhigh%2Bdensity&qid=1681772673&sprefix=ws2813b%2Bled%2Bstrip%2Bhigh%2Bdensity%2Caps%2C69&sr=8-30-spons&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyUUZPR0xCU1BTRFlNJmVuY3J5cHRlZElkPUEwNDg5NDI1TTdWTUJPUDY0NUJGJmVuY3J5cHRlZEFkSWQ9QTAzMjEyNTgyOTUyUFVVTVlURDdKJndpZGdldE5hbWU9c3BfbXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ&th=1)|
|Boost Converter |RP400N501A-TR-FE       |$1.48           |1     |[Click Here](https://www.digikey.com/en/products/detail/nisshinbo-micro-devices-inc/RP400N501A-TR-FE/10244946?s=N4IgTCBcDaIE4AcAsAGFA7ArCgjAQxAF0BfIA)|
|Linear Regulator|LD1117S33TR            |$0.66           |1     |[Click Here](https://www.digikey.com/en/products/detail/stmicroelectronics/LD1117S33TR/585766?s=N4IgTCBcDaIDYBMCMKDsBnAzJgLgJxAF0BfIA)|
|Schottky Diode  |RSX101MM-30TFTR        |$0.45           |1     |[Click Here](https://www.digikey.com/en/products/detail/rohm-semiconductor/RSX101MM-30TFTR/9748173)|
|10uh Inductor   |ASPI-0630LR-100M-T15   |$0.83           |1     |[Click Here](https://www.digikey.com/en/products/detail/abracon-llc/ASPI-0630LR-100M-T15/3059602?s=N4IgTCBcDaIIYGcAOBLAtABgGwGYMBsAnNARgwwFsQBdAXyA)|
|10uF Capactior  |                       |$0.25           |3     |[Click Here](https://www.digikey.com/en/products/detail/murata-electronics/GRM21BR61E106KA73L/2334874)|
|4.7uF Capacitor |                       |$0.10           |1     |[Click Here](https://www.digikey.com/en/products/detail/samsung-electro-mechanics/CL21A475KAQNNNE/3886902)|
|100nF Capacitor |                       |$0.10           |7     |[Click Here](https://www.digikey.com/en/products/detail/yageo/CC0805KRX7R9BB104/302874)|
|JTAG Connector  |FTSH-105-01-H-DV-K-P-TR|$5.63           |1     |[Click Here](https://www.digikey.com/en/products/detail/samtec-inc./FTSH-105-01-H-DV-K-P-TR/9594223?utm_adgroup=Rectangular%20Connectors%20-%20Headers%2C%20Male%20Pins&utm_source=google&utm_medium=cpc&utm_campaign=Shopping_Product_Connectors%2C%20Interconnects_NEW&utm_term=&utm_content=Rectangular%20Connectors%20-%20Headers%2C%20Male%20Pins&gclid=Cj0KCQiAx6ugBhCcARIsAGNmMbh4-y1PB26lYnSIvQfyvOCW9n3EWnzOqesUZbafweeNy_JcrjvtJzoaAvwaEALw_wcB)|
|4.7k Resistor   |                       |$0.10           |2     |[Click Here](https://www.digikey.com/en/products/detail/yageo/RC0402JR-074K7L/726477)|
|500 ohm Resistor|                       |$2.64           |1     |[Click Here](https://www.digikey.com/en/products/detail/vishay-dale/TNPU0805500RAZEN00/6615940)|
|1M Resistor     |                       |$0.10           |1     |[Click Here](https://www.digikey.com/en/products/detail/yageo/RC0805FR-071ML/727445)|
|10MHz Resonator |                       |$0.24           |1     |[Click Here](https://www.digikey.com/en/products/detail/yageo/RC0805FR-071ML/727445)|
|SMD LED         |                       |$0.26           |1     |[Click Here](https://www.digikey.com/en/products/detail/liteon/LTST-C191KRKT/386837)|
|Micro USB Port  |                       |$0.46           |1     |[Click Here](https://www.digikey.com/en/products/detail/amphenol-cs-fci/10118193-0001LF/2785388)|
|Baro Sensor     |LPS22HBTR              |$2.13           |1     |[Click Here](https://www.digikey.com/en/products/detail/stmicroelectronics/LPS22HBTR/5799910)|
