# mystic-crab
Third evaluation based on Github classroom

Morning Evaluation Bobcat

Welcome to the morning Module

Today we will do the morning menu as a Github repository!

First you will need to clone this repository into your workspace folder.

Second you should realise the tasks below

Third when you are finished, write a feed back on the already opened Pull Request and merge it!

Have Fun!!

# Tasks

## Explain me the ultrasonic magic number

In your submission of apex-appraisal, you all used the magic number from ChatGPT in the following function:

```
int getDistance1(){
  digitalWrite(TRIG_PIN, LOW);
  delayMicroseconds(2);
  digitalWrite(TRIG_PIN, HIGH);
  delayMicroseconds(10);
  digitalWrite(TRIG_PIN, LOW);
  return pulseIn(ECHO_PIN, HIGH) / 58;
}
```

Create an issue.

Title : USS Magic Number
Description : Explaining Chat GPT Code

And Submit the issue.

Answer the following question each in 1 comment

1. Please explain me the meaning of 58.

As a reminder:
```
distance = time * speed

speed_of_sound we be approximated to 344 meter per second

1 meter = 100 centimeters = 10^2 centimeters <=> 1 centimeter = 10^-2 m.

pulseIn return the time needed for the pin ECHO_PIN to be HIGH in microseconds

1s = 1 000 000 microseconds = 10^6 microseconds <=> 1 microsecond = 10^-6 s.

The sound will be travelling two time the distance we want to measure.
```