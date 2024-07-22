# Smart-Home
In this project, a smart home with different sensors like  Smoke Detector, PIR, Ultrasonic distance sensor and LDR sensor was built. All these sensors are connected to an Arduino.

Things that you need:
<ul>
  <li>Arduino</li>
  <li>Smoke detector MQ6</li>
  <li>PIR</li>
  <li>LDR</li>
  <li>Ultrasonic Distance Sensor</li>
  <li>Piezo buzzer</li>
  <li>DC power source(Any 12V)</li>
  <li>Relay boards of 2 channels </li>
</ul>

The final view of the circuit is as follows:

![Final_View](https://github.com/user-attachments/assets/cd8ef1ab-72f7-4afb-9dda-a1d75d2e180b)


The functionality of various sensors is as follows:
## 1)Ultrasonic Distance sensor

This is a sensor that detects a person at a certain distance in its range. Whenever it detects a human, it automatically opens the door using a servo motor.

![1](https://github.com/user-attachments/assets/48ae2689-710e-46d4-8a53-3bf951289c8b)

When the person crosses this distance the servo motor is reset to its original position and the door is closed.

![2](https://github.com/user-attachments/assets/ee1cd96b-2192-49c2-9d68-035651fabc53)

## 2)PIR sensor

This is a sensor that detects humans in its surrounding region and will turn on the fan(which runs by a motor).

![3](https://github.com/user-attachments/assets/07e1e1f1-1141-4226-99bd-488d0a9654c6)

When the person goes out of its range it will turn off the fan after a few seconds.

![4](https://github.com/user-attachments/assets/ff32d081-356f-46f0-a751-82eca4ca1c8a)
Here the fan can also be controlled manually in our design using a slide-switch attached to it.

## 3)LDR sensor

This is a sensor which helps us to turn on the lights in the dark or at night time. It will detect the brightness of surroundings and whenever it detects a human it will turn lights ON if it's dark.

![7](https://github.com/user-attachments/assets/b36e7be0-ba64-4184-bae5-5d286966fedc)

When it's day-time, it detects high brightness and switches off the lights.

![8](https://github.com/user-attachments/assets/efea0c11-72ce-4d0d-aef7-4b8f7891115d)

## 4)Smoke Detector
This is a sensor that is connected to a piezo buzzer. When it detects LPG gas around it, the buzzer starts ringing as a caution.

![lpg off](https://user-images.githubusercontent.com/97884235/178326787-6d31dd6c-ff8d-43f3-a144-d46f2c70c92d.png)

![gas on](https://user-images.githubusercontent.com/97884235/178326726-ea3fa240-9d80-4e44-81ce-c84ff7203778.png)

This project is implemented on the Tinkercad platform. The link is attached here-->https://www.tinkercad.com/things/6uZ8fu9XgNH-smart-home/editel?returnTo=%2Fthings%2F6uZ8fu9XgNH-smart-home
