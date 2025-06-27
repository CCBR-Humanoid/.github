<p align="center">
  <h1>Open-Source Humanoid Project</h1>
  <em>A collaboration between Caltech, Columbia, Berkeley, Rutgers (CCBR)</em>
</p>

**We are a team of students building an open-source humanoid robot with modular hardware.**

Our goal is to create a shared platform that lowers the barrier to humanoid robotics research and development.  

---

## 🎯 Objectives
- Develop a cheap, fully functional **bipedal humanoid** capable of walking  
- Create a **modular mechanical and electrical platform** capable of supporting a library of different components (eg, swappable grippers / feet)  
- Build an **open-source community** to advance education and research in humanoid development  

---

## 🦵 Currently: Designing a Modular Leg
We plan to start by creating the leg, which we believe will be helpful for rapid development and in setting the stage to achieve full-body modularity. Our goals for the leg are that:
- The leg can work in both quadrupedal and bipedal settings.  
- Has easily swappable components—sensors, motors, etc.  
- We also want a robust method to estimate the load capacity of any busts the leg would support.  

The most important implication is that we want to design a standard mechanical and electrical attachment interface at our different joints (ankle, knee, hip).

### ⚙️ Ankle modularity
We want to support modular foot geometries (flat pad, gripper toes, wheels, ...) as well as easily swappable motors and sensors (pressure pads, full 6-axis F/T, ...)

### ⚙️ Knee modularity
We also want to support modular knees which will facilitate easier transformations between bipeds and quadrupeds, only requiring a knee replacement rather than an entirely new leg.

### 🔧 Current designs
We are currently exploring a belt-like actuation design where the motors are all centered around the hip joint.

---

## ⏱️ Timeline
| Date        | Milestone |
| ----------- | --------- |
| July 2025   | Leg       |
| Summer 2025 | Quadruped |
| Fall 2025   | Centaur   |
| Spring 2026 | Biped     |

While we are currently working on the leg, we plan to integrate it first into getting a quadruped to walk by the end of summer.

Then in the fall, we plan to develop a human torso which can attach onto the quadruped, creating a "centaur" design capable of manipulation tasks using our quadrupedal base. 

By next year, we hope to integrate them all into a working humanoid.