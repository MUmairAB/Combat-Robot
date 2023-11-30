# Agent of Chaos: A Combat Robot

**This repository contains the files for one of my embedded systems projects that I did back in 2017. The [project report](https://github.com/MUmairAB/Combat-Robot/blob/main/Project%20Report.pdf) contains a detailed description of the project.**

## 1. Introduction

The field of combat robotics is extremely fascinating where different robots fight with the aim of destroying each other. The robots are developed using microcontrollers and various actuators. This project aims to develop a lightweight combat robot capable of incapacitating opponents in an actual competition. We named our robot "Agent of Chaos".

<img src="https://github.com/MUmairAB/Combat-Robot/blob/main/Images/Combat%20Robot%20Example.png?raw=true">

<p align="center">Figure 1: Examples of combat robots</p>

### 1.1 Weight Categories

Just like normal human fighting competitions, these combat robot competitions also have weight categories. The higher the weight category, the more deadly weapons and capabilities the robots possess. Table 1 illustrates various weight categories:

**Table 1: Weight Categories of Combat Robots**

| Sr # | Weight Category | Minimum Weight (kg) | Maximum Weight (kg) |
|-----|------------------|----------------------|----------------------|
| 1   | Featherweight    | 0                    | 10                   |
| 2   | Lightweight      | 10                   | 22                   |
| 3   | Middleweight      | 22                   | 45                   |
| 4   | Heavyweight      | 45                   | 80                   |

## 2. Problem Statement

The cornerstone of this project is to design a combat robot capable of incapacitating the opponent robots in the robot-fighting competition.

## 3. Weapon

The weapon is the paramount component of the robot. It provides both offensive and defensive capabilities. "Agent of Chaos" employs a grinder and a passive flipper as primary weapons, ensuring versatility in combat.

### 3.1 Grinder
- Cordless drill motor with a five-inch blade for crushing opponents. The following figure shows the motor.

<img src="https://github.com/MUmairAB/Combat-Robot/blob/main/Images/DC%20Motor%20For%20Grinder%20Drill.png?raw=true">

<p align="center">Figure 2: Cordless drill motor</p>

### 3.2 Passive Flipper
- Flips over opponents, providing both offensive and defensive capabilities.

## 4. Construction

The overall blueprint of the robot is shown in the following figure. The main emphasis is on lightweight design and efficient operation through an Android app.

<img src="https://github.com/MUmairAB/Combat-Robot/blob/main/Images/Robot%20Circuit.png?raw=true">

<p align="center">Figure 3: Circuit diagram of the robot</p>

## 5. Electrical Specification

### 5.1 Microcontroller
- Arduino microcontroller serves as the brain of the robot, receiving and executing commands.

<img src="https://github.com/MUmairAB/Combat-Robot/blob/main/Images/Arduino%20UNO.png?raw=true">

<p align="center">Figure 4: Arduino microcontroller</p>

### 5.2 DC Motor
- This robot is a four-wheel combat robot. The rear wheels are bigger and mainly control the movement of the robot. They are powered by brushed DC motors for controlled movement. The following figure illustrates the DC motor.

<img src="https://github.com/MUmairAB/Combat-Robot/blob/main/Images/DC%20Motor.jpg?raw=true"> 

<p align="center">Figure 5: 12V DC motor</p>

- Specifications of the DC motor:
  - Diameter: 3.1 in.
  - Length: 4 in.
  - Peak Horsepower: 1.0
  - Peak Torque: 710 oz-in
  - RPM at 24V: 5600 rpm
  - Weight: 1.6 kg

### 5.3 Battery
- Two 12V dry batteries in series, providing power to DC motors.
- Specifications of the DC battery:
  - Volts: 12
  - Ampere: 12 Ah
  - Weight: 3.75 Kg
  - Dimensions: (15 x 6.5 x 9.5) cm

<img src="https://github.com/MUmairAB/Combat-Robot/blob/main/Images/12V%20DC%20Battery.png?raw=true">

<p align="center">Figure 6: 12V DC battery</p>

### 5.4 Motor Driver IC
- L298N motor driver module reverses motor polarity for directional control. It is shown in the following figure.

<img src="https://github.com/MUmairAB/Combat-Robot/blob/main/Images/L298N%20Motor%20Driver%20Module.png?raw=true">

<p align="center">Figure 7: L298N motor driver IC </p>

## 6. Mechanical Specifications

### 6.1 Wheels
- This robot is a four-wheel combat robot. The larger rear wheels (six inches in diameter) control the robot's movement. While The front wheels are swivel casters and move freely.

### 6.2 Body
- Initially, we used steel for the body of the robot. Later on, due to weight constraints, we replaced it with a combination of steel and lightweight fiberglass to meet the 25kg category constraint.

## 7. Bluetooth Control

Remote control is achieved through Bluetooth using the HC-05 Bluetooth Module and an Android app (Bluetooth RC Car app).

<img src="https://github.com/MUmairAB/Combat-Robot/blob/main/Images/HC-05%20Bluetooth%20Module.png?raw=true">

<p align="center">Figure 8: HC-05 Bluetooth Module</p>

## 8. The Final Robot

The following figure shows the final robot. The overall working of the robot can be checked through the [YouTube video](https://www.youtube.com/shorts/3p9OxXeLEPI?t=1&feature=share).

<img src="https://github.com/MUmairAB/Combat-Robot/blob/main/Images/Agent%20of%20chaos.png?raw=true">

<p align="center">Figure 9: Agent of Chaos: A Combat Robot</p>
