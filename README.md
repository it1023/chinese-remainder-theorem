# detector-building
_Norman North's code for Detector Building!_
This code is for Arduino, and maybe in the future we'll support Raspberry Pi!

## Instructions!
You'll need
 - An Arduino Uno
 - Breadboard
 - Jumper cables
 - Three LEDs
 - Resistors with appropriate resistances
 - MF25-103 thermistor
 - LCD monitor (I used an [Adafruit 16x2](https://www.adafruit.com/product/181))
 - Potentiometer (optional)
 
### Setup
Connect the +5V on the Arduino to the red rail on your breadboard and ground to the blue rail. 
 
### LCD Monitor
After ensuring that the header is securely soldered to the LCD, follow the wiring diagram below. Notice that four of the contacts on the LCD aren't used. 

***oops plz imagine that there is a circuit diagram here until I find a good way to display circuit diagrams. The LCD screen is connected to Arduino digital pin outs #7, #8, #9, #10, #11, and #12***

### LEDs
hmm same here... the LEDs are connected to digital pins 4-6 though.

### Thermistor
0.1 uses code that is only compatable with digital thermistors. The one I'm using to test the code is connected to digital pin #2. Updated versions of the software will require the thermistor to be connected to the analog pins and will be rule compliant.

### Code
Open the code in the Arduino IDE. Navigate to Sketch > Include Library > Manage Libraries and install the Adafruit LiquidCrystal library. 
