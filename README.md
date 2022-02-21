# CSC332Project1

Illustrations and prototype examples: https://docs.google.com/presentation/d/1yBgY2pdBv8rbfq0vcSQpZO3umLddCJLjhhLtzsatiZ8/edit?usp=sharing

https://youtu.be/qYAiMQh7Qxw

 
  

**To build the circuit:** 

**Pieces necessary:**

Arduino Uno

Analog Joystick

Breadboard

USB connector

Computer

In our circuit, we used a breadboard to connect the joystick to the Arduino Uno. The wiring is very similar to the image on slide 5. However, the 5V and GND are wired to the breadboard, which is then wired to the joystick. Therefore, the illustration on slide 4 is in reference to how we built it. The photo on slide 6 is the prototype.

 
  
 
**Wiring:**

GND → GND

+5V → 5V

VRx → A1

VRy → A0

SW → ~9
 
 
  

**To run the code:** 

Plug the Arduino Uno into a computer using the USB port. Ensure that the Arduino app is utilizing the correct port. 

Enter the necessary code into both Arduino and Python - we used JupyterLab to run our Python code. 

We found that the best way was to run the Arduino code first. The Python code reads in information from the Arduino’s serial port, so it is best to have that information ready for the Python program.



