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

The robotic arm uses several mechanical constraints to simulate realistic robot motion.

| Joint | Mate Type | Function |
|------|------|-------------|
| Base | Revolute | Rotational base movement |
| Shoulder | Revolute | Main arm lifting motion |
| Elbow | Revolute | Arm extension |
| Wrist | Revolute | End effector orientation |
| Cylindrical Mechanism | Cylindrical | Rotation with linear sliding |
| Gear Transmission | Gear Mate | Synchronizes motion between rotating components |

---

# 🔧 Mates Used

| Mate Type | Purpose |
|-----------|--------|
| Revolute Mate | Creates rotational joints between robot links |
| Cylindrical Mate | Allows rotation with linear sliding |
| Fastened Mate | Rigidly fixes parts together |
| Gear Mate | Synchronizes rotation between components |

These mates simulate realistic robotic joints.

---

# 📷 Assembly View

![Assembly](images/robot-arm-assembly.png)

---

# 🎯 Project Purpose

The purpose of this project was to practice:

- Robot assembly
- Mechanical constraints
- Joint motion
- CAD robot structure
