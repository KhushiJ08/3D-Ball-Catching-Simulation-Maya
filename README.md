# 3D Ball Catching Simulation Using Maya

### Student: Khushi Jatolia  
### Roll No: 24IT3028  
### Course: Graphics & Visualization Computing (GVC)  
### Institute: Rajiv Gandhi Institute of Petroleum Technology (RGIPT), Jais, Amethi  

---

## 📌 Project Overview
This project is a simple 3D ball catching simulation created in Autodesk Maya using Python scripting. The user controls a paddle inside a 3D arena and attempts to catch balls that fall from above. The simulation demonstrates modeling, animation, scripting, UI creation and interaction inside Maya.

---

## 📌 Features
- 3D arena with walls, floor, paddle and ball prototype  
- Ball spawns at random positions  
- Smooth falling motion using keyframe animation  
- Paddle movement using a custom Python UI  
- Score increases on successful catch  
- Automatic ball spawning while the game is running  

---

## 📌 Tools & Technologies
- Autodesk Maya 2026  
- Python (maya.cmds)  
- Maya Script Editor  

---

## 📌 How to Run
1. Open Maya → Script Editor (Python tab)  
2. Import the scripts:
   ```python
   import setup_scene
   import spawn_and_controls

   setup_scene.build_scene()
   spawn_and_controls.show_controls_window()
   spawn_and_controls.start_game()


