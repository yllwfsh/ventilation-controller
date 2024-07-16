# Ventilation Controller
ESPHome configuration for Tecalor Ventilation


### Required Hardware
- A relay board like this: https://amzn.eu/d/0c0mSOhx
- A length of Cat5/6 cable
- Optional: Electronics box to house the relay board in.

### Flash Esphome using the template
To do

### Connect the board
Connect the relay board to the Tecalor module:

- Relay 1 NO to 'Betriebsart' pin
- Relay 2 NO to 'Stufe 0/1' pin
- Relay 3 NO to 'Stufe 2' pin
- Relay 4 NO to 'Stufe 3' pin
- All Relays COM terminals together and to 'Schalter' pin
- Use 24V DC and GND from the ventilation power supply to power relay board.

![Excerpt from Tecalor manual](connections.png)