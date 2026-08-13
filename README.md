# ⚛️ Bohr-Hydrogen-Atom-Simulation-Project

## 📘 Table of Contents
- Visual of Simulation
- Features in Simulation
- Math Concepts in Simulation
- How it Works
- Requirements
- How to Run
- Video Details for Simulation

## 🎨 Visual of Simulation
<img width="567" height="577" alt="Image" src="https://github.com/user-attachments/assets/0209aa90-009c-49b0-afee-5c7ec9e333e6" />

## 🔥 Features in Simulation
- Real time animation using a timer.
- Electron orbiting in a circular motion based on some angle theta. 
- Proton located in the nucleus of the atom.
- Orbital shell guiding the path of the electron.
- 2D representation of the Hydrogen atom. 

## 📝 Math Concepts in Simulation
- Vector Diagram.
- Sine Trigonometric Function.
- Cosine Trigonometric Function.

## 🛠️ How it Works
- The program initializes important variables for the frame, proton, electron, orbital shell, and colors.
- Runs a window with the dimensions of width and height both being 500.
- Sets a HydrogenAtomSimulation panel, which is extended in the JPanel from the public class.
- Timer is used to update the position of the electron from the updateElectron function for every 50 milliseconds.
- The paintComponent is used to draw the proton, electron, and shell in the following panel on the window.
- Variables at the beginning of the program were passed in the Graphics g properties (e.g. g.setColor, g.fillOval, and g.drawOval) to visual each element.

## 🎯 Requirements
- Java (JDK 8 or higher).
- IDE (e.g., VS Code, Eclipse, or IntelliJ).

## 💻 How to Run
  1) Copy the code into a Java file named "HydrogenAtomSimulation.java".
  2) Compile the program: "javac HydrogenAtomSimulation.java".
  3) Run the program: "java HydrogenAtomSimulation".

## 📹 Video Details for Simulation 
I plan to make a YouTube video that will showcase the history behind the Bohr-Rutherford diagram, more deep explanation of how I programmed the project, and share general chemistry knowledge relating to the topic. This video will help give me a reflection on what I learned and for others who are interested in this particular subject and simulation :D.

Video Link of Simulating a Bohr-Rutherford Hydrogen Atom in Java (YouTube) - [2026-09-05!].
