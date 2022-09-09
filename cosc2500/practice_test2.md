# Q1: Micro:Bit
There are 25 edge connector strips/pins on a micro:bit. Of the 25 strips/pins, describe and discuss the different pins and their functions.

There are 3 types of connector pins on the MB chip:
1. Analog pins: For analog data input/output to communicate with connected components.
2. Digital pins: For digital data input/output to communicate with connected components.
3. Power pins: To provide 3V power and ground (GND) connection to power connected components.

Components include sensors, screen, buttons, etc...


# Q2: Guest Lecture
According to the Guest Lecturer, Vietnam is ideal for the IT industry to operate and thrive. He identified the variables that make it ideal and provided several examples. List three variables and back it up with examples.

1. Low labor cost because of growing population.
2. Young, passionate and highly educated IT professionals thanks to a good education system.
3. Fast growing IT industry: Vietnamese companies are moving from taking outsourcing jobs to developing full software solutions, thus the demand for IT worker is also increasing.


# Q3: Arduino
In this project, the LED lights is turned on when we cover the LDR sensor and is turned off when the LDR sensor is exposed to light. The circuit is as follows: [Image](https://rmit.instructure.com/courses/104889/files/26979464/preview)


```
#define LDR_IN A0
#define LED_OUT 11
#define THRESHOLD 300


void setup() {
  pinMode(LDR_IN, INPUT);
  pinMode(LED_OUT, OUTPUT);
}

void loop() {
  if (analogRead(LDR_IN) < THRESHOLD) {
    digitalWrite(LED_OUT, HIGH);
  } else {
    digitalWrite(LED_IN, LOW);
  }
}
```


# Q4: Raspberry Pi
What are NOOBS and Raspbian OS? Is there any difference between the two? Explain.

NOOBS is an OS installer. We download and install NOOBS so that it can install the an operating system on the Raspberry Pi (Raspbian or other).

Raspbian is the working OS that you use for whatever purpose you want. You can install Raspbian directly from an image (not using NOOBS).


# Q5: Network Model
In the OSI model of network transmission, there are 7 layers namely in order: Application, Presentation, Session, Transport, Network, Datalink, and Physical. Describe the process of layering (data go through each layer) with an example application.
