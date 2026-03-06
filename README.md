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

- Base platform
- Lower arm
- Upper arm
- Wrist joint
- End effector (gripper)

All parts were assembled in **Onshape Assembly Studio**.

---

# ⚙️ Joint System

The robot arm movement is controlled using **Revolute mates**.

| Joint | Type | Description |
|------|------|-------------|
| Base | Revolute | Rotates the entire robot |
| Shoulder | Revolute | Moves the main arm |
| Elbow | Revolute | Extends the arm |
| Wrist | Revolute | Adjusts end effector orientation |

---

# 🔧 Mates Used

The following mates were used to construct the robot:

- Revolute Mate
- Fastened Mate

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
