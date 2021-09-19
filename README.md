# Pop_Can_Piano
This is a simple project created with pop cans /soda cans and ArduinoDUE
The main application of this project is to make pop cans play as piano keys.

## MATERIALS
- ArduinoDUE
- Breadboard
- Wires
- Resistors (1 Mohm)
- Alligator clips
- Speaker

## THE BUILD: 
One side of the 1MOhm resistor will be connected to a common pin on the ArduinoDUE board 
The other side with digital pins on DUE and to the pop-cans with alligator clips 
The speaker will be connected to ground & an output pin.

## HOW DOES IT WORK?
When we touch the conductive object ( in our case the soda cans but you can use any conductive material and it will work) the capacitance rises, the sensor ( resistors ) will detect this rise and will send this information to the board, the board will then choose a certain sound to play and the speaker will play it.

### Links
Video demonstration:
https://www.youtube.com/watch?v=wMYpshIueS8 

https://create.arduino.cc/projecthub/rayta/pop-can-piano-fb6f4a?ref=user&ref_id=1821539&offset=0
