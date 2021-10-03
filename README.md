# radar-using-arduino
How to make a radar using arduino

Parts we needed to make this project:
Hardware

    Arduino UNO
    HC-SR04 Ultrasonic Sensor  
    TowerPro SG90 Servo Motor  
    Mounting Bracket for Ultrasonic Sensor 
    Connecting Wires  
    Jumper Cables  
    5V Power Supply  
    USB Cable   

Software

    Arduino IDE (https://www.arduino.cc/en/software)
    Processing Application (https://processing.org/download)


How does Radar Work?

The word RADAR means Radio Detection And Ranging. Radar is an object detection system that uses microwaves to determine the range, altitude, direction, and speed of objects within about a 100-mile radius of their location.
The radar antenna transmits radio waves or microwaves that bounce off any object in their path. Due to this, we can easily determine the object in the radar range.

The basic principle of operation:

A radar is an electromagnetic sensor that is used to detect and locate an object.
Radio waves or microwaves are radiated out from the radar into free space. Some of these waves are intercepted by reflecting objects.
These intercepted radio waves hit the target and are reflected in many different directions. Some of these waves can be directed back toward the radar, where they are received and amplified.
If these waves are received again at their origin, then it means an object is in the propagation direction.
The modern radar system is very advanced and used in highly diverse applications such as Air traffic control, Air-defence system, radar Astronomy, Antimissile system, Outer space Surveillance system, and many more.

What is Ultrasonic Sensor?

An ultrasonic sensor is a proximity sensor that is used to measure the distance of a target or object. It detects the object by transmitting ultrasonic waves and converts the reflected waves into an electrical signal. These sound waves travel faster than the speed of the sound that humans can hear.
It has two main components: the transmitter & receiver. The transmitter emits the sound using a piezoelectric crystal, and the receiver encounters the sound after it has travelled to and from the target.
For the calculation of the object distance, the sensor measures the time taken by the signal to travel between the transmission of the sound by the transmitter to the reflecting back towards the receiver.

The formula for this calculation is,
D = ½ T x C 
Where,
    D = distance,
    T = time
    C = speed of sound which is 343 meters/second.
    
What is Servo Motor?

The servo motor is a simple DC motor that can be controlled for specific angular rotation with the help of additional servomechanism. This motor will only rotate as much we want and then stop. The servo motor is a closed-loop mechanism that uses positional feedback to control the speed and position.
This closed-loop system includes a control circuit, servo motor, shaft, potentiometer, drive gears, amplifier, and either an encoder or resolver.
The servo motor is unlike a standard electric motor which starts and stops according to the power input. According to the signal, the servo motor will work.
Nowadays, servo motors are widely used in industrial and robotics applications. They are also commonly seen in remote-controlled toy cars, RC planes, and in the CD or DVD player. Besides these, we see hundreds of applications in our daily life that use a servo motor. To know more about the servo motor, refer to the servo motor working principle.


![Arduino-Radar-Project-Image-1](https://user-images.githubusercontent.com/91609293/135743883-d419048a-967b-493e-b696-cafeceb360c4.jpg)

Hardware Connection

The below image shows the connection of the Arduino radar project. The connections are very simple. Here, we have interfaced the ultrasonic sensor and servo motor with an Arduino Uno. The connection details are,

Arduino Uno	      Ultrasonic Sensor	      Servo Motor
    Vcc	                 Vcc	                Vcc
    Gnd	                 Gnd	                Gnd
    D10	                 Trig	                 -
    D11	                 Echo	                 -
    D12	                  -	                 Signal   


![Arduino-Radar-Project-Circuit-Diagram](https://user-images.githubusercontent.com/91609293/135743886-c4207a4d-d666-4bc5-b82a-fc0e7311ad00.jpg)


