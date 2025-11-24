# Insulin-Pump-Simulator

A simulation for the Tandem t:slim X2 insulin pump using Qt/C++.


<p align="center">
  <img src="https://github.com/user-attachments/assets/519f03c6-9471-48b6-a1f3-40b804dae75d"
       alt="insulin_pump"
       width="100%">
</p>



## Contributors
Kamal Yassin 

Hamzah Hamad 

Thu Thu Chit Pyae 

Justin Schoenhofer 

Aidan Casselman

## Responsibilities
1. Project Planning
- Outline team responsibilities, schedule and timeline 
- Plan the design 
- Create GitHub repository 

2. Design
- Use cases 
- Use Case Diagram 
- UML class diagram 
- UML state machine diagram 
- UML sequence diagram 
- Requirements Traceability Matrix & Test Video 
- An explanation of our design decisions

3. Development
- User Interface class, home.ui screen, CGM-charts, button interactions (options, bolus, history), login (pin), screen layout policies 
- Settings (CRUD) and PumpController 
- Basic device functions and control flow
- Data storage, logging, history, profile management, and documentation 
- Bolus calculator and manual bolus operation (.cpp, .h, .ui), ControlIQ (.cpp, .h) 

## File Organization

### Root Directory
`InsulinPumpSimulator-Group35-main/`

---

### UML Diagrams
Located in `Design-Documentation/`:
- `Sequence-Diagrams/`
    - `Create-Profile.png`
    - `Low-Battery.png`
    - `Main-Device-Loop.png`
    - `Manual-Bolus.png`
    - `Update-Profile.png`
    - `View-History.png`

- `Design-Explanation.pdf`
- `State-Diagrams.pdf`
- `Traceability-Matrix.pdf`
- `UML-Class-Diagram.png`
- `Use-Cases.pdf`
- `Use-Case-Diagram.png`

---

### Source Code
Located in `code/`:
- `main.cpp`
- `batterymanager.cpp`, `batterymanager.h`
- `boluscalculator.cpp`, `boluscalculator.h`, `boluscalculator.ui`
- `cgmreader.cpp`, `cgmreader.h`
- `controliqalgorithm.cpp`, `controliqalgorithm.h`
- `datalogger.cpp`, `datalogger.h`
- `device.cpp`, `device.h`, `device.ui`
- `history.cpp`, `history.h`, `history.ui`
- `home.cpp`, `home.h`, `home.ui`
- `insulinreserve.cpp`, `insulinreserve.h`
- `login.cpp`, `login.h`, `login.ui`
- `profile.cpp`, `profile.h`
- `pumpcontroller.cpp`, `pumpcontroller.h`
- `settings.cpp`, `settings.h`, `settings.ui`
- `userinterface.cpp`, `userinterface.h`, `userinterface.ui`
- `alert.cpp`, `alert.h`, `alert.ui`
- `bloodstream.cpp`, `bloodstream.h`

---

### Test Video
- `Test-Video.mp4`

## Documentation

[View the full project documentation here](https://xhwahx.github.io/InsulinPumpSimulator-Group35/)

## Compiling instructions
Make sure QtCharts is installed: `sudo apt install libqt5charts5-dev`

### In the terminal:
First, navigate to the `code/` directory:

- `cd code/`

Then run:

- `qmake insulinPump.pro`
- `make`
- `./insulinPump`

### In Qt Creator:
- Open `insulinPump.pro`
- Press **Build**
- Press **Run**
