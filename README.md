
=======
# TOASTDUINO aftermarket toaster oven controller


Whether you are doing advanced engineering on a limited budget, or you just really like toast, ToastDuino is for you.

ToastDuino is an aftermarket temperature controller for retrofitting your average toaster oven into a piece of extraordinary equipment.



Notes:

Most [package name] relays draw around 80mA coil current. The part number I recommend is [part number]because they draw only 60mA. This is important becuase the PBK-1-5 can output only 200mA, and switching both relays at the same time could cause an overcurrent condition. An alternative to using [part number] is to add a 100ms delay betwen switching each relay, and distribute the inrush current over a longer time period. 

Pins 10 and 11 are not available for GPIO because the SPI library allocated them for communication. 

Pin A2 has a pull-up resistor installed for easy connection to a pushbutton.
