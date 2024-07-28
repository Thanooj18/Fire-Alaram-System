FIRE detection using embedded components like Arduino board (e.g., Arduino Uno) Fire sensor module
Buzzer
GSM modem (e.g., SIM800L)
SIM card with an active plan for call.
and connections as :
Connect the fire sensor module to the Arduino board. Typically, fire sensors have three pins: VCC, GND, and OUT. Connect VCC to 5V on the Arduino, GND to GND, and OUT to a digital input pin (e.g., pin 2).

Connect the buzzer to the Arduino. Connect one pin of the buzzer to a digital output pin (e.g., pin 3) and the other pin to GND.
Connect the GSM modem to the Arduino. Make the following connections:
GSM modem RX to Arduino TX (digital pin 10) GSM modem TX to Arduino RX (digital pin 11) GSM modem VCC to Arduino 5V
GSM modem GND to Arduino GND Open a new sketch in the Arduino IDE. 
i have uploaded complete report and arduino code too.
