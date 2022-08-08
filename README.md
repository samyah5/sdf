# task1-Electronics-and-electrical-power
* Running the servo motor on the Arduino
* Running the brushless motor on the Arduino

## Running the servo motor on the Arduino

**Hardware Required** 
1. servo motor
2. Arduino Uno
3. connecting wires
4. Arduino wire

**STEP1: Connecting the servo motor circuit**
![image](https://user-images.githubusercontent.com/108360083/183415088-60203128-3f65-4005-972e-500d10a9288b.png)

**STEP2: Uploading the code to the Arduino microcontroller**

Open the code: File> Examples> Servo> Sweep
```
#include <Servo.h>

Servo myservo;  // create servo object to control a servo
// twelve servo objects can be created on most boards

int pos = 0;    // variable to store the servo position

void setup() {
  myservo.attach(9);  // attaches the servo on pin 9 to the servo object
  myservo.write(90);   
}
```

https://user-images.githubusercontent.com/108360083/183418168-a5df57e0-ed32-4e2f-8f45-daad2c977e57.mov



## Running the brushless motor on the Arduino
