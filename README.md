# 🤖 Robot Arm Assembly (Onshape)

This project demonstrates the assembly of a robotic arm using **public CAD components in Onshape**.

The focus of this project was on:

- Mechanical assembly
- Joint configuration
- Revolute mate setup
- Robot kinematics simulation

Rather than designing parts from scratch, the components were sourced from public Onshape parts and assembled into a functional robotic arm.

---

# 🖼 Robot Arm Preview

<img width="685" height="947" alt="لقطة شاشة 2026-03-06 181005" src="https://github.com/user-attachments/assets/238e8433-b595-4b30-9fed-52ccdbbf37ba" />


---

# 🧩 Assembly Structure

The robotic arm assembly consists of multiple links connected through rotational joints.

Main components:

1. Base del brazo y circuito
2. Tapa circuito
3. Eje Central
4. Engranaje1
5. Engranaje2
6. Barra1
7. Barra2
8. Brazo
9. Antebrazo
10. Base de la Garra
11. Garra1
12. Garra2

All parts were assembled in **Onshape Assembly Studio**.

---

# ⚙️ Joint System

The robotic arm movement is controlled using different mate constraints configured in the Onshape assembly.

| Joint Area | Mate Type | Description |
|-------------|-------------|-------------|
| Base Structure | Fastened | The base covers are rigidly fixed to the main base structure |
| Base Rotation | Revolute | Allows the circular platform to rotate the entire robot arm |
| Shoulder Joint | Revolute | Connects the base to the first arm segment |
| Elbow Joint | Revolute | Enables bending motion between the arm links |
| Intermediate Link | Cylindrical + Revolute | Allows both rotation and slight sliding motion between link components |
| Wrist Joint | Revolute | Controls orientation of the end-effector |
| Gripper Mechanism | Gear Mate | Synchronizes the rotation of the gripper gears |

---


# 📷 Assembly View

<img width="433" height="533" alt="image" src="https://github.com/user-attachments/assets/a3c3094c-6b94-45a7-a189-f7a80464b2a0" />

---


# 🎥 Robot Motion Demo

Watch the robot arm in motion:

https://youtu.be/WXS4-cyEAZk?si=KpW7XBwalOi5TZQG

---


# 🎯 Project Purpose

The purpose of this project was to practice:

- Robot assembly
- Mechanical constraints
- Joint motion
- CAD robot structure
