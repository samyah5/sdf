# task1-Electronics-and-electrical-power
* Running the servo motor on the Arduino
* Running the brushless motor on the Arduino

## Running the servo motor on the Arduino

**Hardware Required** 
1. servo motor
2. Arduino Uno
3.  USB Cable for arduino UNO
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

**Hardware Required** 
1. brushless motor 
2. Arduino Uno
3. USB Cable for arduino UNO
4. Arduino wire
5. Relay
6. power 
7. breadboard


**STEP1: Connecting the brushless motor circuit**
![image](https://user-images.githubusercontent.com/108360083/183435528-fd4d69ee-7ff1-44ce-bedd-6d4c4cac2bcf.png)

**STEP2: Uploading the code**

Open the code : File> Examples> Basics> Blink

```
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(LED_BUILTIN, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(1000);                       // wait for a second
  digitalWrite(LED_BUILTIN, LOW);    // turn the LED off by making the voltage LOW
  delay(1000);                       // wait for a second
}
```


https://user-images.githubusercontent.com/108360083/183437547-e54bdc3f-6dc3-4e74-903f-6dfe3b00b5f4.mov




