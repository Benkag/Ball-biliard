# Basic introduction to the program
This program is a simulation of a billiard parallel programming problem, written in Java (NetBeans).
Users can choose different maps, each with unique start and goal points — with Map 2 and Map 3 containing obstacles for added challenge.
Before starting, players can input the number of balls — the more balls there are, the smaller each ball becomes.
When the user clicks “Start”, the balls appear and start moving, and the program predicts which ball will fall into the hole first.
This is a visual simulation designed to help learners understand multithreading and graphical interaction in Java Swing.

# How to Run the Program
🔧 1. Requirements

- Java JDK 8 or later

- NetBeans IDE (or IntelliJ/Eclipse)

- Make sure JDK is added to system PATH

2. Running the Code

- Open NetBeans

- Go to File → New Project → Java Application
- Name it BilliardSimulation

- Copy all the Java files (Main.java, Map.java, Ball.java, etc.) into the src folder

- Ensure Main.java contains:

public static void main(String[] args) {
    new GameFrame(); // or new MainFrame();
}


- Press Run (Shift + F6) to start the program

3. Using the Program

- Choose a map: Map 1, Map 2, or Map 3

- Enter number of balls (e.g., 10, 20, 30)
       More balls → smaller ball size

- Click “Start” to begin

- Balls appear and move

- Program predicts which ball falls into the hole first

- When a ball reaches the hole, a result message will appear

# DEMO Video Play Game
---->  https://youtu.be/TzE5QaHqkGQ


