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
├── week-01/
│   ├── slides.pdf
│   └── lab-notes.pdf
├── week-02/
├── week-03/
│   ...
└── week-15/
```

Each `week-XX/` folder holds that week's slide deck and lab notes once the week has been taught. Folders are added as the semester progresses.

## Weekly Schedule

| Week | Theory | Practice / Lab |
|---|---|---|
| 1 | Introduction to Visual Programming and Java Swing | First Swing application; JFrame and JPanel |
| 2 | Basic Swing Components I | JLabel, JButton, JTextField, JPasswordField |
| 3 | Basic Swing Components II | JCheckBox, JRadioButton, ButtonGroup, JComboBox |
| 4 | Advanced Swing Components | JTextArea, JList, JScrollPane, JSlider, JSpinner, JProgressBar |
| 5 | Event-Driven Programming | ActionListener and component interaction |
| 6 | Layout Management | Organizing GUI components using layout managers |
| 7 | Data and Collections in GUI Applications | ArrayList, Iterator, and managing application data |
| 8 | **Midterm Examination** | — |
| 9 | Tables and Data-Oriented Interfaces | JTable, DefaultTableModel; add/update/delete; project launch |
| 10 | Object-Oriented GUI Design | Classes, encapsulation, inheritance, polymorphism; project development |
| 11 | Graphics and Custom Drawing | Graphics, paintComponent(), shapes, colors, repaint(); project development |
| 12 | Interactive Graphics and Events | Mouse and keyboard events, KeyListener, interactive graphical objects |
| 13 | Project Development I | GUI architecture, components, data model, application logic |
| 14 | Project Development II | Integration, event handling, testing, refinement |
| 15 | Project Presentation and Evaluation | Project demonstration, presentation, and evaluation |

## Semester Project

Students design and build an **educational game for children aged 7–10** as a Java Swing desktop application, targeting one of:

- Basic mathematical operations (addition, subtraction, multiplication, division) through interactive exercises
- Cognitive / logical reasoning skills — pattern recognition, memory, or problem-solving challenges

The project combines GUI components, event handling, data management, and object-oriented design, with custom graphics and/or keyboard/mouse interaction appropriate for young learners. Work begins after the midterm and runs through Weeks 9–15, ending with a final demonstration and presentation.

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
