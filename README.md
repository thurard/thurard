<!-- Ce README s'affiche sur ta page de profil s'il est dans un dépôt PUBLIC nommé exactement "thurard". -->

# Tom Hurard

### Robotics & Mechatronics Engineering Student — SeaTech (University of Toulon)

I build and simulate systems that move — mobile robots, controlled mechanical
systems, embedded prototypes. My work runs from the physics and control theory
(modelling in MATLAB/Simulink, controller design) down to the embedded code and
the real hardware (ROS 2, computer vision, microcontrollers, CAD and 3D
printing).

I am in the final year of my engineering degree (Master's level) on the SYSMER
track — marine and robotic systems — and I am **looking for a 6-month
end-of-studies internship starting March 2027**, in France, in robotics,
mechatronics, systems engineering (MBSE) or embedded automation.

- Based in La Valette-du-Var / Toulon, France
- [LinkedIn](https://www.linkedin.com/in/tom-hurard) · tom.hurard30@gmail.com

---

## Current internship — KMUTNB, Bangkok (2026)

Research intern in the Department of Production and Robotics Engineering,
building a complete autonomous robot from navigation to manipulation:

- Deployed a full autonomous navigation stack (ROS 2 Foxy, Nav2, Cartographer
  SLAM) on an AgileX LIMO mobile robot running an NVIDIA Jetson Xavier NX.
- Integrated YOLOv8 with RGB-D depth data for real-time 3D object detection and
  spatial localization.
- Built an end-to-end vision-guided grasping pipeline (visual servoing in joint
  space) for a myCobot 280 arm, compensating for 3–5 cm positioning error of the
  mobile base.
- Wrote an autonomous patrol program in Python with dynamic obstacle recovery
  and automated anomaly reporting (HTML/CSV).
- Set up reliable multi-machine communication with CycloneDDS over a
  Wi-Fi/Ethernet bridge.

---

## Projects

### Robotics

| Project | What it is | Tech |
|---|---|---|
| [Move–Perceive–Grasp (LIMO + myCobot)](https://github.com/thurard/limo-mycobot-move-perceive-grasp) | The internship pipeline above: a LIMO robot patrols and detects objects, a myCobot arm grasps them via visual servoing, linked over a socket bridge | ROS 2 · Python · OpenCV · YOLOv8 |
| [ROS TurtleBot Obstacle Avoidance](https://github.com/thurard/ros-turtlebot-obstacle-avoidance) | Finite-state-machine navigation on a TurtleBot 2, using LIDAR and bumper feedback to explore and avoid obstacles | ROS · Python |
| [dsPIC Obstacle-Avoiding Robot](https://github.com/thurard/dspic33-obstacle-avoidance-robot) | Bare-metal firmware for an autonomous mobile robot — PWM motor control, IR range sensing and finite-state navigation on a dsPIC33 | C · dsPIC33 |

### Modelling & control

| Project | What it is | Tech |
|---|---|---|
| [ABS Braking (Simulink)](https://github.com/thurard/abs-braking-simulink) | Modelling and control of an anti-lock braking system: physical tyre/wheel/vehicle model, then PI, discrete, bang-bang and dead-zone controllers, plus electronic brakeforce distribution (EBD) with load transfer | MATLAB/Simulink |
| [Vehicle Dynamics Simulator](https://github.com/thurard/performance-dynamique-vehicule) | Bicycle model with a Pacejka tyre, built up to a closed-loop AE86 vs FC3S duel where the overtake emerges from the physics rather than a script | MATLAB |
| [Gyro-Stabilized Hydrofoil Drone](https://github.com/thurard/gyro-stabilized-hydrofoil-drone) | Multi-year project with industrial partner ZYX Blue on an RC foiling drone kept level by a gyroscope — Simulink modelling, a redesigned SolidWorks foil, embedded system and repeatable pool take-offs | MATLAB/Simulink · SolidWorks |

I am also studying Active Disturbance Rejection Control (ADRC), applied in Python
to a wave-compensating arm.

---

## Skills

- **Robotics & autonomy:** ROS / ROS 2, Nav2, Cartographer (SLAM), CycloneDDS, visual servoing
- **Computer vision & AI:** OpenCV, YOLOv8, RGB-D depth cameras, 3D object localization
- **Programming:** Python, C, C++, Java, MATLAB / Simulink, SQL
- **Embedded & hardware:** NVIDIA Jetson Xavier NX, dsPIC33, AgileX LIMO, myCobot 280
- **Engineering & tools:** SolidWorks, 3D printing, Linux (Ubuntu), Git, LaTeX

## Education

- **Engineering degree (Master's) — Robotics & Mechatronics**, SeaTech, University of Toulon (2024–2027). SYSMER track: marine and robotic systems. Minor in entrepreneurship.
- **CPGE** — intensive preparatory program, Maths/Physics/Chemistry (2022–2024).

## Languages

English (B2, TOEIC 895) · French (native) · Spanish (intermediate) · Chinese (basic)
