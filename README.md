# YZ 203 — Visual Programming

**Java Swing & Event-Driven Programming**
Erciyes University

This repository hosts the weekly lecture slides, lab notes, and code examples for YZ 203.

## Instructor & Teaching Assistants

| Role | Name | Email |
|---|---|---|
| Instructor | Murat AKPULAT, PhD | muratakpulat@erciyes.edu.tr |


## Course Description

An introduction to visual and event-driven programming with Java Swing: GUI containers, components, layout managers, event handling, object-oriented GUI design, collections, graphical drawing, and user interaction. Each topic pairs theory with hands-on lab practice. After the midterm, students design and build a semester project that integrates these concepts.

## Repository Structure

```
.
├── README.md
├── Week_1/
│   ├── <slides>.pdf
│   └── <lab notes>.pdf
├── Week_2/
├── Week_3/
│   ...
├── Week_9/
└── Week_10/
```

Each `Week_N/` folder holds that week's slide deck and lab practice notes (PDF) once the week has been taught. Folders are added as the semester progresses.

Weeks are numbered by the sessions actually taught, so holidays and the midterm week are not counted.

## Weekly Schedule

| Week | Theory | Practice / Lab |
|---|---|---|
| 1 | Setup, introduction and basic components I | First Swing application; JFrame, JPanel and basic components |
| 2 | Selection, text and value components | Selection, text and value components in small applications |
| 3 | Timer and animation basics | `javax.swing.Timer`, moving objects, simple animation |
| 4 | Graphics and `paintComponent` | Custom drawing, shapes, colors, `repaint()` |
| 5 | Keyboard, mouse and collision | Key and mouse events, collision detection, interactive objects |
| 6 | Reinforcement lab | Short examples that revise Weeks 1–5 (no new slides) |
| 7 | ArrayList and Iterator | Lists of objects, safe removal, Falling Egg with many eggs |
| 8 | JTable and DefaultTableModel | Add, delete, select and edit rows; top-5 score board; project launch |
| 9 | Multi-screen games | CardLayout, Navigator, back stack, menu bar, key bindings, screen lifecycle |
| 10 | File I/O | `Files`, buffered streams, `JFileChooser`, CSV, `Properties`; persistent scores and settings |

The midterm examination is practical and is held between the instructional weeks, so it has no week number.

**Next:** project development, integration, and the final project presentations. Dates are announced in class.

## Semester Project

Students design and build an **educational game for children aged 7–10** as a Java Swing desktop application, targeting one of:

- Basic mathematical operations (addition, subtraction, multiplication, division) through interactive exercises
- Cognitive / logical reasoning skills — pattern recognition, memory, or problem-solving challenges

The project combines GUI components, event handling, data management, and object-oriented design, with custom graphics and/or keyboard/mouse interaction appropriate for young learners. The project is launched in Week 8, and the last weeks of the semester are used for project development, ending with a final demonstration and presentation.

**This semester's running example:** an egg-catching game — eggs fall from the top of the screen and the player moves a basket left/right with the keyboard to catch them. Built up incrementally from Week 1's first JFrame through `Timer`, `Graphics`, and `KeyListener` in later weeks, this example is used throughout the course to introduce new topics and can be extended by students into other games.

## Assessment

- Laboratory / assignment work
- Midterm examination
- Semester project
- Final examination

*(Exact percentage weights are announced by the instructor.)*

## Tools

- **JDK** — a current LTS release (Eclipse Temurin / Oracle JDK)
- **NetBeans** (or another Java IDE) — the GUI Builder / drag-and-drop designer is **not used** in this course; every component is written by hand in code

## License

Course materials are provided for YZ 203 students at Erciyes University. Please don't redistribute outside the course without the instructor's permission.
