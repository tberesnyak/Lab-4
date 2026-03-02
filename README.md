# Lab-4
Lab 4 Microcontroller
Tom Beresnyak and Pat Faust
3/2/2026
Introduction or Summary:
In this lab we used the RedBoard and Arduino IDE to control a LED. This was done inturn to demonstrate a comparing circuit and a PWM. Inturn we saw how a timer, comparing circuit, and PWM can be used to simulate different percived voltages which led to flashing or persistance in the LED. 
Methods/Tests: Engineering documentation necessary to repeat the project. Should include:
The original code for the lab was the following.
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);  // turn the LED on (HIGH is the voltage level)
  delay(1000);                      // wait for a second
  digitalWrite(LED_BUILTIN, LOW);   // turn the LED off by making the voltage LOW
  delay(1000);                      // wait for a second
}
Results:

<img width="280" height="240" alt="Lab 4" src="https://github.com/user-attachments/assets/3ace38d1-3269-4a5d-a506-9ec1fcfabf28" />
These were values given out by the light sensor.
<img width="1284" height="955" alt="Screenshot 2026-02-17 130213" src="https://github.com/user-attachments/assets/f29e9e86-9bb2-4278-a70e-0ab381ae6868" />
This was edited code for part 2.
<img width="982" height="535" alt="Screenshot 2026-02-17 135249" src="https://github.com/user-attachments/assets/57f5a21c-f2e1-4f90-a1b8-9b9de0fa8eb2" />
This was edited code for part 3.
Discussion:
1. a. The value we found for it to stay consistent was 12 miliseconds.
   b.c. This plays a greater role in videos and movies where a flashing light is used to simulate motion on a screen or projector. Being able to flash at a high enough rate to trick the mind into stable light helps with simulated stable motion.
2. a. An analog signal is a fluid signal that has no smallest unit. It can be any number along its path. A digital signal has a finite digit to every part of it. It can only have so many integers.
   b. Analog signals are something like a sound wave or light. A digital signal is something like a singal to a sprayer head which sets it to on or off. A digital signal can only be in the state of on or off.
   c. The serial monitor refresh rate goes from 0 to 1023.
3. a. It quicking turns off while taking a second to turn off. This is because of how the code is set. The value given by the sensor controls the refresh rate. So when it is block is is a lower number leading to a delay while the code runs.
4. a. A digital wave is shown on the oscilloscope. The peak seen on the oscilloscope is from parasitic capacitance.
Conclusion: Most important things derived/learned from the lab and report (one or two paragraphs).
