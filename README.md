# Wokwi Microcontroller Projects

A collection of **microcontroller projects** developed in **C/C++** and simulated using **Wokwi**. These projects demonstrate embedded systems concepts, hardware interaction, and microcontroller programming, making them perfect for learning and portfolio showcases.  

Each project contains two key files:  

- `sketch.ino` — The Arduino code  
- `diagram.json` — The Wokwi simulation setup (pins, components, circuit layout)  

---

## Folder Structure
```
wokwi-microcontroller-projects/
├── binary-counter/
│   ├── sketch.ino
│   └── diagram.json
├── project-2/
│   ├── sketch.ino
│   └── diagram.json
└── project-n/
    ├── sketch.ino
    └── diagram.json
```
> Each project folder is self-contained with its own Arduino code and Wokwi diagram.

---

## How to Use a Project in Wokwi

Follow these steps to run any project from this repository:

1. **Open Wokwi**  
   Go to [https://wokwi.com/](https://wokwi.com/) and log in or continue as a guest.

2. **Create a New Project**  
   - Click **“New Project” → “Arduino Uno”** (or the board specified in the project).  
   - Wokwi will create a blank project with a default `sketch.ino`.

3. **Copy the Arduino Code**  
   - Open the `sketch.ino` file from the project folder.  
   - Copy all its content.  
   - Paste it into the `sketch.ino` file in your new Wokwi project, replacing any existing code.

4. **Import the Circuit Diagram**  
   - Open the `diagram.json` file from the project folder.  
   - Copy its entire content.  
   - In Wokwi, click **“File” → “Import JSON”**, paste the JSON content, and confirm.  
   - The circuit will be recreated exactly as in the original project.

5. **Run the Simulation**  
   - Click **“Start Simulation”**.  
   - Interact with components (buttons, LEDs, etc.) as needed.  
   - The project should now run exactly like intended.

---

## Tips & Notes

- Always copy **the entire content** of both files. Partial copying may cause errors.  
- Make sure the Arduino board in Wokwi matches the one used in the project (usually **Arduino Uno**).  
- You can rename folders to better describe the projects as you add more.  
- This repository is a growing collection — more projects will be added over time.

---


