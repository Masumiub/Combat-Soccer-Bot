# Combat-Soccer-Bot
Designing a combat soccer bot with Arduino and motor controller.

# Elements
- Arduino- Uno (Quantity - 1)
- Buck converter (Quantity - 1)
- BTS 7960 Motor controller (Quantity - 2)
- Shaft coupler short (Quantity - 4)
- Flat wheel (Quantity - 4)
- Bracket 36mm Mount (Quantity - 4)
- 300 RPM DC 37mm motor (Quantity - 4)
- HC-05 Bluetooth Module (Quantity - 1)
- T-connector (Quantity - 1) 
- Battery 2200mAh (Quantity - 1)
- Charger B3 (Quantity - 1)

# Procedure:
1. Connect the Bluetooth module with the Arduino to pins according to the diagram. Connect the 5v 
pin and ground of the Arduino to power up Bluetooth module.
2. Connect the motors parallelly & connect the positive & negative wires according to the BTS 
motor’s to the M+ & M- point. Now connect the battery with the motor controller with B+ & B - point. Then connect another motor controller parallelly.
3. Connect another 2 parallelly connected motors with the motor controller.
4. Connect the motor controllers’ pin with the Arduino according to the circuit diagram.
5. Connect the battery with buck converter, adjust the buck converter’s voltage to 5v and connect 
the output wires(Vout+, Vout-) to the Vin & ground pin with Arduino and motor controllers’ 
VCC and ground pins.
6. Upload the code to the Arduino board.
7. Power on the Arduino and pair the HC-05 Bluetooth module with your phone.
8. Install the "Bluetooth RC car" app on your phone.
9. Open the app, connect to the HC-05 module, and use the on-screen buttons to send commands to 
control the RC car or soccer bot.
