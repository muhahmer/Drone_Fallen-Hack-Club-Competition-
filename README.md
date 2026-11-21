# The Racing Drone
> Total Cost to Manufacture: 575 USD

## About My Project

#### What Is My Project? 
Designed for Fallen Hack Club Competition this Project is meant to surpass commercial drone's capabilities. Being made up of similar components GPS, gyroscopes, motor drivers this drone is capable of things that most commercial drones are unable to do such as RTH (return to home function) transmit high frequency video feed, give live stats on drone's battery and more. While also having codable functions this drone also holds capabilities (expected) to go at much faster speeds with a thrust to weight ratio of 4:1. In addition this drone also brings innovation to the marked with the single handed screen remote. Many high end companies combine their single hand controller with over expensive VRs where as this project has developed a way that a single hand controller integrated with a screen (non VR) using servos to tilt the screen according to the hand movement when controlling the drone.

#### Why I Made This?
The Reason I made this goes back many years to when I was a young kid (around 6 years old) when I first aspired to make my own drone. I made designs clueless on how it would work just driven by the love of drones. Later when I started getting into Arduino, which opened doors for me, I understood how real drones would work but still unable to make my own. As this competition has come up it has given me the opportunity to fill my childhood dream and make my very own custom drone, built by my own hands and designed by my own hands.

### Design Screenshots
>Controller PCB
<img width="619" height="473" alt="image" src="https://github.com/user-attachments/assets/ad3576c3-58c7-44dd-aeb4-49da31300e15" />

>Controller CAD
<img width="1920" height="984" alt="Fallen Drone Project#-2026-11-15 165346" src="https://github.com/user-attachments/assets/46cbaa04-4000-4f6b-97db-727de89d1fcc" />


>Drone PCB
<img width="565" height="493" alt="image" src="https://github.com/user-attachments/assets/6d60be8c-6be0-451f-ae46-a0847fcca18d" />


>Drone CAD
<img width="691" height="372" alt="image" src="https://github.com/user-attachments/assets/60d64795-39d2-4f5c-9e6c-03d4419d583e" />
<img width="758" height="494" alt="image" src="https://github.com/user-attachments/assets/8beeda98-6dcd-460f-9722-b88b2d37cfbc" />



## Key Features
** Key Features ** 
- High quality FPV Camera
- Custom Single Hand ESP Controller
- Motion Assisted Dynamic Tiltable Screen
- GPS Telemetry and Safety Functions

  ### Controller Pin layout
  Joystick:
  - X axis connected to pin 32 of ESP
  - Y axis connected to pin 33 of ESP
  - Joystick Button connected to pin 25 of ESP

 Rotary Encoder 1 (Screen tilt controller 1):
  - Rotation Counter connected to pin 26 of ESP
  - Direction Counter connected to pin 27 of ESP
  - Rotary Encoder button connected to pin 12 of ESP

 Rotary Encoder 2 (Screen tilt controller 2) :
  - Rotation Counter connected to pin 19 of ESP
  - Direction Counter connected to pin 23 of ESP
  - Rotary Encoder button connected to pin 14 of ESP 

 Rotary Encoder 3 (Camera tilt controller)
  - Rotation Counter Connected to pin 16 of ESP 
  - Direction Counter connected to pin 17 of ESP
  - Rotary Encoder button connected to pin 4 of ESP  
  
  #### Drone Pin Layout
