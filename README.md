## Adafruit LoRa Radio Bonnet with OLED - RFM95W @ 915MHz - RadioFruit PCB

<a href="http://www.adafruit.com/products/4074"><img src="assets/4074.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit LoRa Radio Bonnet with OLED - RFM95W @ 915MHz - RadioFruit. Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4074

### Description

The latest Raspberry Pi computers come with WiFi and Bluetooth, and now you can add even more radio options with the Adafruit Radio Bonnets! Upgrade your Raspberry Pi with a LoRa / LoRaWAN radio, so it can communicate over very long distances. These bonnets plug right into your Pi and give you long range wireless capabilities to remote nodes that may be battery powered. Or, you can create Internet gateways with ease.

You not only get a radio module, but also a 128x32 OLED display for status messages and three buttons you can use for creating a custom user interface or sending test messages. All of the above is supported with our Python libraries so you can send or receive LoRa data with other matching modules, send data to a LoRaWAN gateway, or even set up your own single channel LoRaWAN-to-Internet gateways.

Compared to the 2.4 GHz WiFi/Bluetooth radios on the Pi already, these modules run at 433 or 900 MHz (sub-GHz). You can't send data as fast but you can send data a lot farther. These packet radios are simpler than WiFi or BLE, you don't have to associate, pair, scan, or worry about connections. All you do is send data whenever you like, and any other modules tuned to that same frequency (and, with the same encryption key) will receive. The receiver can then send a reply back. The modules do packetization, error correction and can also auto-retransmit so it's not like you have worry about everything but less power is wasted on maintaining a link or pairing.

These modules are great for use with other microcontrollers with matching radios (like say our [RadioFruit Feathers](https://www.adafruit.com/?q=radiofruit%20feather)), say if you want a sensor node network or transmit data over a campus or town. The trade off is you need two or more radios, with matching frequencies.

These radio modules come in four variants (two modulation types and two frequencies) The RFM69's are easiest to work with, and are well known and understood. The LoRa radios are exciting and more powerful but also more expensive.

**This is the 900 MHz LoRa radio version, which can be used for either 868MHz or 915MHz transmission/reception** - the exact radio frequency is determined when you load the software since it can be tuned around dynamically. These are +20dBm LoRa packet radios that have a special radio modulation that is not compatible with the RFM69s but can go much much farther. They can easily go 2 Km line of sight using simple wire antennas, or up to 20Km with directional antennas and settings tweakings

 * Packet radio with ready-to-go CircuitPython libraries
 * Uses the license-free ISM band: "European ISM" @ 868MHz or "American ISM" @ 915MHz
 * Use a simple wire antenna or spot for uFL or SMA radio connector
 * SX1276 LoRa® based module with SPI interface
 * +5 to +20 dBm up to 100 mW Power Output Capability (power output selectable in software)
 * ~100mA peak during +20dBm transmit, ~30mA during active radio listening.
 * Range of approx. 2Km, depending on obstructions, frequency, antenna and power output
All radios are sold individually and can only talk to radios of the same part number. E.g. RFM69 900 MHz can only talk to RFM69 900 MHz, LoRa 433 MHz can only talk to LoRa 433, etc.

Each bonnet comes fully assembled and ready to go. You can attach an antenna via the uFL connector, or cut and solder on a small piece of wire (any solid or stranded core is fine) in order to create your antenna.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
