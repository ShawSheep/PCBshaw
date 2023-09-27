# Arduino on a Breadboard
## Assignment's description
Use the ATmega328 to build Arduino on a Breadboard
## Documentation
bullet point list
* Basic knowledge of ATmega328
* Connect the circuit
* Use the Arduino IDE test the circuit

numbered list

**Basic knowledge of ATmega328**

![picture description](./images/ATmega328.jpg)

**1.All of the supplies**

To make an arduino on a breadboard,what we need is all there.

![picture description](./images/All-of-the-supplies.jpg)

**2.Add ATmega328**

Firstly,we plug the ATmega328 which is the core of the arduino into the breadboard.

![picture description](./images/Add-ATmega328.jpg)

**3.Add two wires**

Use two lines to link the two sides of the breadboard,assuring current can flow on both sides.

![picture description](./images/Add-two-wires.jpg)

**4.Add voltage regulator**

Plug the Voltage Regulator and the capacitor to the breadboard,which can reduce the voltage from the external battery if the voltage is too high. And the capacitor can stablize the voltage in circuit. 

![picture description](./images/Add-voltage-regulator.jpg)

**5.Add a LED**

Plug one LED to the breadboard to detect if there have current in circuit and then to know when the ATmega328 is powered.

![picture description](./images/Add-a-LED.jpg)

**6.Add supporting power**

Use wires to make sure that current can flow into the ATmega328. And use a resistence(10k) to prevent the chip from resetting itself during normal operation.

![picture description](./images/Add-supporting-power.jpg)

**7.Add a crystal oscillator**

Add a crystal oscillator between the Pin9 and10,and add 2 capacitors(22pf) between ground and the two Pins.

![picture description](./images/Add-a-crystal-oscillator.jpg)

**8.Add a USB**

Use a USB(CP2120) link the computer and the board. The connection order is "VCC to +;GND to -;RXD to Pin3(TXD on the ATmega328);TXD to Pin2(RXD on the ATmega328);DTR to Pin1 and between the two need a capacitor.

![picture description](./images/Add-a-USB.jpg)

**9.Current can flow**

Connect the USB to the computer,the LED is on,to illustrate that current can correctly flow.

![picture description](./images/Current-can-flow.jpg)

**10.Control LED**

Use the Pin19 on the ATmega328(Pin13 on the Arduino Uno) to control the LED to flash. And the code is from case in Arduino IDE.

![picture description](./images/Control-LED-02.jpg)

**11.Adrduino IDE**

Code test on Arduino IDE

![picture description](./images/Code.png)
